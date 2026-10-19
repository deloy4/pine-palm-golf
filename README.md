# Pine & Palm Golf

A 3D golf game for the browser. Play it at https://deloy4.github.io/pine-palm-golf/ in Chrome on a computer.
There is no build step: `index.html` runs as it is, and GitHub Pages serves the `main` branch, so pushing to
`main` updates the site.

You swing with the mouse. Hold the left button, pull the mouse straight back to set the distance, then push it
forward through where you started. Slant the push to draw or fade the ball, scroll to add or take off loft, and
use Q and E (or the follow-through, from the Spin by menu) for more or less backspin.

## The courses

All four courses are made up, in a Florida style with pines, oaks, palms, waste areas and water. Each is par 72.

| Course | Style | Yards |
| --- | --- | --- |
| Heronwood, Heron Course | Waste areas and lakes, a forced-carry par 3 at 17 | 6,999 |
| Coquina Ridge, Ridge Course | Hills, elevated tees, up to about 30 feet of drop | 7,035 |
| Palmetto Run, Lakes Course | Water on most holes, reachable par 5s, drivable par 4s | 7,040 |
| Blackwater Bend, Oak Course | Tight oak corridors, creeks, small greens | 7,030 |

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner oaks.

## Scores

Finish a "Play 18 holes" round and the scorecard offers Record score. Each course has its own board on the
shared arcade scoreboard (game `golf-<course id>`), and golf boards rank the lowest round first.

## The golfer

The golfer is a Mixamo character with Mixamo's drive, chip and putt animations, converted to `golfer.glb`.
Mixamo content may be used in games but not handed out as standalone files, so don't reuse `golfer.glb`
outside this game.
