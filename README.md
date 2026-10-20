# Pine & Palm Golf

A 3D golf game for the browser. Play it at https://deloy4.github.io/pine-palm-golf/ in Chrome on a computer.
There is no build step: `index.html` runs as it is, and GitHub Pages serves the `main` branch, so pushing to
`main` updates the site.

You swing with the mouse. Hold the left button, pull the mouse straight back to set the distance, then push it
forward through where you started. Slant the push to draw or fade the ball and scroll to add or take off loft.
Backspin comes from the follow-through: stop short just past where you started for more, keep pushing through
for less.

Off the short grass the lie matters. Rough, pine straw, waste areas, beaches, rocks and bunkers each roll a lie when the
ball stops (in rough it can sit up, sit in the grass or sit down; in sand it can lie clean or plug), and every shot from
there comes out a little different. A wedge cuts through and stays close to its normal distance; a long iron or a wood
gets grabbed and comes out shorter and much less predictable, and it can be caught heavy. A ball sitting up in rough can
come out as a flier, long and with no spin. The projected flight and the carry always show the clean-lie shot, as if from
the fairway, so the player has to work out how much the lie will take off.

## The courses

All sixteen courses are made up. The first four are in a Florida style with pines, oaks, palms, waste areas and
water; the next four are on the ocean, with cliffs, beaches, coves and surf; the next four are in mountain
forest, with big elevation changes, hillsides, creeks and ranges on the horizon; the last four are on tropical
islands, with lava or coral shores, palms, flowering shrubs and mountains inland. Each is par 72, about 7,250 to 7,450
yards, with sharp doglegs whose corners can be carried, holes that bend around water, a drivable par 4, par 5s reachable in
two only over trouble, and fairways that tilt toward hazards.

| Course | Style | Yards |
| --- | --- | --- |
| Heronwood, Heron Course | Sharp doglegs with corners to cut, a drivable 5th, a par 5 at 16 reachable over water, a forced-carry par 3 at 17 | 7,300 |
| Coquina Ridge, Ridge Course | Hills and elevated tees, sharp doglegs at 3, 9 and 17, capes over lakes at 6 and 13, a drivable downhill 11th, par 5s at 2 and 8 reachable over water | 7,275 |
| Palmetto Run, Lakes Course | Water on almost every hole, sharp doglegs at 3, 6 and 12, drivable 5th and 15th, par 5s at 2 and 16 reachable over water, a cape finish along the lake | 7,250 |
| Blackwater Bend, Oak Course | Tight oak corridors, sharp doglegs at 3, 10 and 15, a drivable 6th, creeks in front of the greens at 2, 11 and 13, a cape finish over water | 7,330 |
| Cormorant Head, Cliffs Course | Clifftop holes, doglegs around sea coves at 3, 6 and 8, a drivable 14 on the cliff edge, par 5s at 2 and 18 reachable over a cove, a long cove carry at 16 | 7,290 |
| Gullhaven Dunes, Dunes Course | Wide beaches and sand blowouts, sharp doglegs at 2, 9, 13 and 17, a drivable 8th, par 5s at 4 and 11 reachable over water, fairways tilting toward the beach | 7,270 |
| Driftwood Shoals, Ocean Course | Beach holes and lagoons, sharp doglegs at 3, 9 and 15, a drivable 6th by the beach, par 5s at 2, 13 and 16 reachable over water | 7,310 |
| Kestrel Bluffs, Canyon Course | Bluffs 90 to 130 feet above the sea, sandy canyons across 3, 4, 9 and 16, cove carries at 2, 10, 12 and 17, a drivable 5th, par 5s at 8 and 13 reachable over a cove | 7,352 |
| Talus Ridge, Summit Course | Big drops from high tees, sharp doglegs at 4, 10 and 14, a lake cape at 11, a drivable 5th, a par 3 at 7 that drops 140 feet | 7,430 |
| Osprey Creek, River Course | A creek on most holes, capes over the water at 2 and 14, a drivable 5th across the creek, par 5s at 9 and 13 reachable over water | 7,255 |
| Kettle Lake, Lake Course | Tight firs and kettle lakes, sharp doglegs at 2, 6 and 13, lakes to bite off at 5 and 15, a drivable 11th, a par 3 at 16 that drops 100 feet over a lake | 7,430 |
| Sourwood Gap, Gap Course | Fall hardwoods and creek hollows, sharp doglegs at 2, 8 and 14, a drivable 6th, par 5s at 9 and 16 reachable over a creek, a par 3 at 13 that drops about 115 feet | 7,350 |
| Frigate Point, Lava Course | Lava fields and cliffs, a cape 9th across a sea cove, coves to carry at 3, 11 and 16, a drivable 5th, par 5s at 8 and 18 reachable over coves | 7,315 |
| Tern Reef, Beach Course | White sand beaches and lagoons, capes over lagoons at 4 and 17, a drivable 6th, a short carry to a green by the beach at 11 | 7,260 |
| Petrel Cliffs, Cliffs Course | Clifftop holes above the sea with jungle corners to cut, bays to carry at 2 and 17, a drivable 5th, a cove par 3 at 12 | 7,285 |
| Tropicbird Bay, Reef Course | Holes along the low coral shore with fairways tilting to the sea, bays to carry at 9 and 12, a drivable 6th, a par 3 to a point at 11 | 7,280 |

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner trees. `open` cuts
clearings into the woods ([yards along, yards across, radius]) so the inside of a dogleg can be carried, and `stand` leaves a
clump of trees inside the corridor. `tilt` ([from, to, feet]) tips the ground across the fairway so a ball landing on the
low side runs toward the hazard there (feet fallen across 30 yards, plus to the right). Greenside bunkers are dug deeper than fairway bunkers, with a higher lip. Ocean holes
add `sea`, a list of straight shorelines given by two points along and across the hole, with an optional beach
width; the course settings choose the trees, the scrub colour and the wind. Mountain holes add `side`, how many
feet the hillside climbs about 100 yards off the line of play (plus for the right, minus for the left), and `wl`,
the water level in feet for a creek or pond up in the hills; the course's `range` sets the mountains around it.
Island courses are ocean courses with a `range` as well, which puts mountains (and an optional volcano, `cone`)
inland behind the far land; `pal.cliff` and `pal.sand` colour the shore rock and the beach.

## Scores

Finish a "Play 18 holes" round and the scorecard offers Record score. In an 18-hole round each hole is played
once; Replay hole is only offered when playing a single hole. Each course has its own board on the
shared arcade scoreboard (game `golf-<course id>`), and golf boards rank the lowest round first.

## The golfer

The golfer is a Mixamo character with Mixamo's drive, chip and putt animations, converted to `golfer.glb`.
Mixamo content may be used in games but not handed out as standalone files, so don't reuse `golfer.glb`
outside this game.
