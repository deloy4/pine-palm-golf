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
islands, with lava or coral shores, palms, flowering shrubs and mountains inland. Each is par 72.

| Course | Style | Yards |
| --- | --- | --- |
| Heronwood, Heron Course | Sharp doglegs with corners to cut, a drivable 5th, a par 5 at 16 reachable over water, a forced-carry par 3 at 17 | 7,300 |
| Coquina Ridge, Ridge Course | Hills, elevated tees, up to about 30 feet of drop | 7,035 |
| Palmetto Run, Lakes Course | Water on most holes, reachable par 5s, drivable par 4s | 7,040 |
| Blackwater Bend, Oak Course | Tight oak corridors, creeks, small greens | 7,030 |
| Cormorant Head, Cliffs Course | Clifftop holes with cypress, carries over sea coves at 3, 6, 8 and 16 | 7,030 |
| Gullhaven Dunes, Dunes Course | Wide beaches, big dunes and sand blowouts, few trees, the windiest | 6,960 |
| Driftwood Shoals, Ocean Course | Beach holes and lagoons, live oaks and palms | 7,050 |
| Kestrel Bluffs, Canyon Course | Bluffs about 90 feet above the sea, sandy canyons across the holes | 7,055 |
| Talus Ridge, Summit Course | Colorado spruce and gold aspens, snow peaks, a par 3 at 7 that drops 140 feet | 7,235 |
| Osprey Creek, River Course | A Montana valley with a creek on most holes, lodgepole pines and a far range | 7,085 |
| Kettle Lake, Lake Course | Tight Cascade firs, lakes, a snow-capped volcano on the horizon | 7,120 |
| Sourwood Gap, Gap Course | Blue Ridge hardwoods in fall colour, rolling holes, a par 3 at 13 that drops about 115 feet | 7,050 |
| Frigate Point, Lava Course | Black lava fields and cliffs, coves to carry at 3 and 16, a volcano inland | 7,120 |
| Tern Reef, Beach Course | White sand beaches, palms and bougainvillea, lagoons, green ridges inland | 6,995 |
| Petrel Cliffs, Cliffs Course | Red cliffs about 100 feet above the sea, jungle, sharp green ridges close by | 7,120 |
| Tropicbird Bay, Reef Course | Low coral rock along the sea for whole holes, a par 3 to a point at 11 | 7,015 |

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner trees. `open` cuts
clearings into the woods ([yards along, yards across, radius]) so the inside of a dogleg can be carried, and `stand` leaves a
clump of trees inside the corridor. Greenside bunkers are dug deeper than fairway bunkers, with a higher lip. Ocean holes
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
