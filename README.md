# Pine & Palm Golf

A 3D golf game for the browser. Play it at https://deloy4.github.io/pine-palm-golf/ in Chrome on a computer.
There is no build step: `index.html` runs as it is, and GitHub Pages serves the `main` branch, so pushing to
`main` updates the site.

You swing with the mouse. Hold the left button, pull the mouse straight back to set the distance, then push it
forward through where you started. Slant the push to draw or fade the ball and scroll to add or take off loft.
Backspin comes from the follow-through: stop short just past where you started for more, keep pushing through
for less.

## The courses

All eight courses are made up. The first four are in a Florida style with pines, oaks, palms, waste areas and
water; the other four are on the ocean, with cliffs, beaches, coves and surf. Each is par 72.

| Course | Style | Yards |
| --- | --- | --- |
| Heronwood, Heron Course | Waste areas and lakes, a forced-carry par 3 at 17 | 6,999 |
| Coquina Ridge, Ridge Course | Hills, elevated tees, up to about 30 feet of drop | 7,035 |
| Palmetto Run, Lakes Course | Water on most holes, reachable par 5s, drivable par 4s | 7,040 |
| Blackwater Bend, Oak Course | Tight oak corridors, creeks, small greens | 7,030 |
| Cormorant Head, Cliffs Course | Clifftop holes with cypress, carries over sea coves at 3, 6, 8 and 16 | 7,030 |
| Gullhaven Dunes, Dunes Course | Wide beaches, big dunes and sand blowouts, few trees, the windiest | 6,960 |
| Driftwood Shoals, Ocean Course | Beach holes and lagoons, live oaks and palms | 7,050 |
| Kestrel Bluffs, Canyon Course | Bluffs about 90 feet above the sea, sandy canyons across the holes | 7,055 |

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner trees. Ocean holes
add `sea`, a list of straight shorelines given by two points along and across the hole, with an optional beach
width; the course settings choose the trees, the scrub colour and the wind.

## Scores

Finish a "Play 18 holes" round and the scorecard offers Record score. In an 18-hole round each hole is played
once; Replay hole is only offered when playing a single hole. Each course has its own board on the
shared arcade scoreboard (game `golf-<course id>`), and golf boards rank the lowest round first.

## The golfer

The golfer is a Mixamo character with Mixamo's drive, chip and putt animations, converted to `golfer.glb`.
Mixamo content may be used in games but not handed out as standalone files, so don't reuse `golfer.glb`
outside this game.
