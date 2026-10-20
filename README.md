# Pine & Palm Golf

A 3D golf game for the browser. Play it at https://deloy4.github.io/pine-palm-golf/ in Chrome on a computer.
There is no build step: `index.html` runs as it is, and GitHub Pages serves the `main` branch, so pushing to
`main` updates the site.

You swing with the mouse. Hold the left button, pull the mouse straight back to set the distance, then push it
forward through where you started. Slant the push to draw or fade the ball and scroll to add or take off loft. On a phone the swing is the same with a
finger, and buttons at the bottom left change the club and loft and turn the aim (hold to turn, tap to nudge); the panels
shrink to the edges of the screen upright or on its side.
Backspin comes from the follow-through: stop short just past where you started for more, keep pushing through
for less. The ball plays back at twice real speed (putts at two and a half times), and Space speeds it up more. When the
ball is in or at the edge of the trees, Drop (or the X key) moves it to the nearest clear spot with an open shot, no nearer
the hole, for a one-stroke penalty.

Off the short grass the lie matters. Rough, pine straw, waste areas, beaches, rocks and bunkers each roll a lie when the
ball stops (in rough it can sit up, sit in the grass or sit down; in sand it can lie clean or plug), and every shot from
there comes out a little different. A wedge cuts through and stays close to its normal distance; a long iron or a wood
gets grabbed and comes out shorter and much less predictable, and it can be caught heavy. A ball sitting up in rough can
come out as a flier, long and with no spin. The projected flight and the carry always show the clean-lie shot, as if from
the fairway, so the player has to work out how much the lie will take off.

Elevation works the same way. The projected flight, the carry readout and the club numbers show the carry over level
ground, and the panel shows how far the pin sits above or below the ball. The ball itself flies the real hill: in this
ball flight a 6 iron carries about 10 yards farther to a green 30 feet below and about 11 yards shorter to one 30 feet
above, close to the usual rule of a yard for every 3 feet, so the player has to pick the club for the drop or the climb.

## The courses

All twenty courses are made up. The first four are in a Florida style with pines, oaks, palms, waste areas and
water; the next four are on the ocean, with cliffs, beaches, coves and surf; the next four are in mountain
forest, with big elevation changes, hillsides, creeks and ranges on the horizon; the next four are on tropical
islands, with lava or coral shores, palms, flowering shrubs and mountains inland; the last four are in the desert,
with saguaros, junipers, dry washes and red rock, where a ball that misses the fairway and its thin band of rough lies in
the desert, on hardpan or in the rocks. Each is par 72, about 7,250 to 7,450
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
| Roadrunner Wash, Desert Course | Saguaro foothills with dry washes on most holes, sharp doglegs at 3, 7 and 12, a drivable 6th over a pond, a par 3 at 8 that drops 70 feet over a deep wash, a par 5 at 17 reachable over water | 7,340 |
| Condor Canyon, Canyon Course | Red rock canyon holes with tees on the rim dropping up to 207 feet, approaches climbing up to 115 feet onto the mesa, deep washes in the canyon floor, sharp doglegs at 4, 7 and 13, a 232-yard par 3 at 3 that drops 186 feet | 7,408 |
| Piñon Mesa, Mesa Course | High desert under snowy peaks, doglegs at 4, 10 and 15 with desert corners to cut, a lake to carry at 11, a drivable downhill 5th, par 5s at 2 and 13 reachable over a pond and a deep arroyo, a par 3 at 7 that drops 120 feet off the mesa | 7,292 |
| Verdin Springs, Oasis Course | Lakes on most holes, sharp doglegs at 4, 8, 11 and 15, an island fairway at 14, a peninsula green at 12, par 5s at 2 and 13 reachable over water, a finish climbing into the mountains | 7,340 |

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner trees. `open` cuts
clearings into the woods ([yards along, yards across, radius]) so the inside of a dogleg can be carried, and `stand` leaves a
clump of trees inside the corridor. `tilt` ([from, to, feet]) tips the ground across the fairway so a ball landing on the
low side runs toward the hazard there (feet fallen across 30 yards, plus to the right). Greenside bunkers are dug deeper than fairway bunkers, with a higher lip. Ocean holes
add `sea`, a list of straight shorelines given by two points along and across the hole, with an optional beach
width; the course settings choose the trees, the scrub colour and the wind. Mountain holes add `side`, how many
feet the hillside climbs about 100 yards off the line of play (plus for the right, minus for the left), and `wl`,
the water level in feet for a creek or pond up in the hills; the course's `range` sets the mountains around it.
Desert courses are mountain courses with `desert: true`: `pal.floor` is `sonoran`, `redrock` or `highdesert`, `flora`
can list `saguaro`, `ocotillo`, `joshua`, `juniper`, `paloverde`, `hardwood` and `palm`, `edgeMix` weighs the plants along
the edge of the rough (`shrub`, `barrel`, `ocotillo`), `lakeC` colours the lakes and `range.mesa` steps the far range into
flat benches and cliffs. A water entry `{ t: 'wash', s0, s1, d0, d1, dep }` is a dry wash, a sandy channel `dep` feet
deep (4 by default) that plays as a waste area.
Island courses are ocean courses with a `range` as well, which puts mountains (and an optional volcano, `cone`)
inland behind the far land; `pal.cliff` and `pal.sand` colour the shore rock and the beach.

## Scores

The home screen is one screen: tabs for the terrains (Florida, Ocean, Mountain, Island and Desert) above that terrain's four
courses, and clicking a course opens it in place with its course record, Play for a score, Practice and its leaderboard.
Play for a score starts at the 1st tee and plays all 18 holes once; finishing the 18th opens the scorecard with Post to
leaderboard. Leaving a score round early (Menu, after a check) ends it with no score. Practice opens the 18 holes under
the course; the player picks any hole, replays it, and moves between holes with the Hole and Restart buttons; nothing is
recorded. Each course has its own board on the shared arcade scoreboard (game `golf-<course id>`), and golf boards rank the
lowest round first.

## Players and progress

Sign-in is the arcade's shared one (`auth-v1.js` from https://deloy4.github.io/bfg/, repo deloy4/bfg): one player name
and PIN, or email, for every game on deloy4.github.io, and signing in on the BFG page or in another game signs you in
here too. Without that file (the page opened somewhere it can't load it) the game plays as a guest. Only signed-in
players can post to the golf boards; the database refuses golf scores sent the old way.

Only finished score rounds count. A score round keeps what it records with the round while it is played and adds it
to the player's progress when the 18th is holed; a round ended early, or a closed tab, leaves nothing behind, and practice
never records anything. Score rounds record, hole by hole: the result (hole in one, albatross, eagle, birdie, par, bogey, double or worse),
fairways hit on par 4s and 5s, greens in regulation, putts, and shots holed from off the green and from bunkers. Shots
record personal bests: the longest drive ending in the fairway or first cut, the longest putt holed, and the longest shot
holed from the fringe, fairway, rough, a bunker and anywhere else. Achievements mark the first birdie, eagle, albatross,
hole in one, chip-in, hole-out from the sand, finished round and round under par, with a count of each. New ones, with
the round's XP, trophies, unlocks and handicap change, show on the card after the 18th; everything shows on the profile page (Profile and stats on the home screen), with a
summary of each course played. Practice records nothing.

A guest's progress is kept on the device and moves to the account at sign-in; unsent holes are kept per player, so
signing out never hands them to the next player. Progress goes to the database as deltas (`golf_push`): counts add,
personal bests keep the larger and achievements keep the first, so two devices can't undo each other. Golf's tables
(`golf_progress`, `golf_rounds`, `golf_pushes`) sit beside the shared `players` and `sessions` in the arcade-scores
Supabase project and are only reached through the `golf_*` functions.

## Levels, handicap, trophies and unlocks

XP comes from the score-round counts (10 a hole, more for fairways, greens in regulation, pars, birdies and better,
chip-ins, finished rounds and rounds under par) and sets a level from 1 to 99. The handicap follows the real system: the
best 8 differentials of the last 20 finished score rounds, fewer with the official adjustments until there are 20, shown
from the third round. A differential is the score minus the course rating, and `golf_ratings` works each course's rating
out from every player's rounds (each round against that player's own average, pulled toward par until a course has a good
number of rounds). Each course gives a bronze, silver or gold trophy for the best round (+10, +5, par) and a badge for a
birdie or better on all 18 holes across its rounds. Florida is open; each next terrain opens once two courses on the one
before have a round at +5 or better, and Verdin Springs also needs a round under par. Locked courses can't be practised.

## Next build: achievement pop-ups

Achievements should be seen when they happen, not only on the last hole's card. Plan: when a shot earns an achievement
(or a personal best), a small pop-up slides in at the top of the screen with the achievement's name and one line under
it, holds about three seconds with a short sound, and queues behind any other pop-up. Because only finished score rounds
count, the pop-up says it counts when the round is finished; the card after the 18th still lists everything that was
saved, and a round ended early saves none of it. The news is already collected per round (`G.round.news` through
`newsFor`), so the pop-up hooks in there. Still to decide with Chris: whether other players should see achievements too
(for example a recent-achievements list on the home screen or the BFG portal), and whether personal bests pop up or only
achievements.

## The golfer

The golfer is a Mixamo character with Mixamo's drive, chip and putt animations, converted to `golfer.glb`.
Mixamo content may be used in games but not handed out as standalone files, so don't reuse `golfer.glb`
outside this game.
