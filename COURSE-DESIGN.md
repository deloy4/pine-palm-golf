# Course design: risk and reward

Read this before building or redesigning any course. Chris wrote these rules on 2026-10-21. Every risk/reward hole on a
new course has to follow them, and every one has to be checked with shot sweeps in the real hole before it ships.

## The rule behind all of them

In this game a 100-yard shot and a 150-yard shot are both easy. So a risky line that only leaves a shorter approach is
worth nothing, and a player has no reason to take it. A risk only pays when it changes the score: it reaches the green
on a par 4 for an eagle or birdie putt, or reaches a par 5 in two. If the safe shot and the risky shot leave the same
number of strokes to the hole, the hole is badly designed.

The safe play is a clean 100% shot. It lands somewhere easy and leaves a plain par. The risky play needs more than 100%:
up to 112% power, a draw for the extra roll and carry, a fade around something, or the right wind. It has to land in a
small spot, and the miss has to cost a stroke or close to it. A miss that ends up in ordinary rough 20 yards from where
the good shot went is no punishment.

## 1. Driving a par 4 green

A 100% driver lands short of the green and leaves an easy chip and putt for birdie. A 112% driver with a slight draw can
run onto the green, but the landing zone for that shot is narrow: half of the fairway at that distance slopes into water
(`tilt` toward the lake). The player chooses between 100% and an easy up and down, or 112% plus a draw that has to land in
one spot to roll onto the green.

## 2. Par 5 shortcut over the dogleg

The shortcut can be over woods or over water.

On a wooded hole there is a gap in the canopy, so a driver can fly over the trees and land on a small pad (`alt` landing
pad). A plain 100% shot doesn't make it. Getting there needs something more: a draw for the extra carry, carrying into a
strong crosswind, or a tailwind on the day. Short or long of the pad, the ball is in thick trees that need a drop or a
pitch out.

On a water hole a miss is in the water. A water hole can also put a tree on the straight line to the island or pad, so
the player has to draw or fade around it to hit the landing zone.

## 3. Dogleg par 4

If the player takes the corner off the tee and pulls it off, the green has to be reachable from there (driven, or one
easy short shot for an eagle-range putt on a short hole). If the green can't be reached by cutting the corner, there is
no reason to cut it, because rule one says a 100-yard approach is no better than a 150-yard one. Size the hole so the
cut changes the score, or don't offer the cut.

## 4. Long par 4 or par 5 with a clean 100% landing zone

At 100% the landing zone is clean, but the green can't be reached with the second shot, so there is no eagle putt. A
draw for extra distance can set up a second shot to the green, but the landing zone at that distance is hard: a narrow
fairway, big bunkers, or water right beside the fairway with the ground sloping into it. A shot above 100% has to be
exact. If it lands in the bunker or off the fairway, the rough there has to be very hard to get out of.

## 5. Long par 4 with a dogleg shortcut

Taking the shortcut has to cost something when it fails. Two ways to build it:

There is a narrow gap in the trees near the end of the shortcut. A drive that misses the gap leaves the player having to
pitch out sideways or take a drop before they have a clean shot.

Or the distance is set so it takes a full 112% shot with a fade to get there. A shot that comes up short is behind an
obstacle (trees, a mound, a stand) that makes the second shot very hard, or is in the water and loses a stroke.

## Checking a hole

Before a risk/reward hole is done, run shot sweeps through the real hole and confirm three things. The local helpers
`_golftest.js` and `_golfsweep.js` (kept out of git) do this in a `#test` page: `fly()` sends one exact shot (100% or 112%,
a draw or fade as face against path, any aim and wind) through the hole and reports where it stops, and `swXY()` sweeps a
row of aims round a point on the map. A straight 100% shot does not reach the reward. The risky shot (112%, the
draw or fade, the wind it needs) does reach it inside a small aim window, a few degrees, not a wide one. And the misses on
either side of that window land in the penalty the hole promises: water, a drop or a pitch-out. Write the
measured windows into the hole's notes in the README.
