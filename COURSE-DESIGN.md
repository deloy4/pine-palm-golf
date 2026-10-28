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

## Fairways, rough and bunkers

Chris played the Links, Parkland and Quarry courses on 2026-10-27. He liked how they were designed but found them a
little easy: the fairways were still easy to hit, a missed fairway did not cost enough, and a couple of bunkers could not
be escaped. Those courses stay as they are. These rules are for the next courses.

Make the fairway in a driving zone 20 to 30 yards wide, most of them 24 to 26, not the 32 to 40 used on those courses.
Keep the rough beside it a thin band, about 10 yards, so a drive that misses by more than that is in the trouble past it:
gorse, woods, rubble or a pit. `cor` is the half-width of that corridor, so set it to about half the fairway width plus 10.

Make a missed fairway cost close to a stroke on a long hole. The rough lie model today takes about 17% off a mid
iron from an average lie and 30% when the ball sits down. A deeper rough for the course (more balls sitting down, about 70% of the stock distance from an
average lie) was tried in test sweeps, but Chris set aside a 50% rough on 2026-10-21, so ask him before adding it.

Every bunker has to be escapable with a sand wedge or lob wedge from wherever the ball stops in it, including at the foot
of the face nearest the green. The pot bunker shape in the game now (bunker entry `[..., 1]`) is about 2.2 m from lip to
floor with the face reached 1.6 m in, and a full sand wedge from the foot of that face stays in the bunker on almost every
pot. A pot 1.2 m deep with the face reached 2 m in let a wedge out from about 96% of spots while a 4 iron or 7 iron still
caught the face two times in three. Change the pot shape before the next course that uses pots, and check every bunker
with a wedge from its centre and from the foot of the face nearest the pin.

## Greens

Chris, 2026-10-28: greens have to be harder. Each green needs a specific landing zone, and an approach that misses it
should leave a two-putt that is hard to make.

The greens on the Links, Parkland and Quarry courses average about 180 square yards (`rx` × `ry`). Each one is a single
surface: a back-to-front tilt and a few random swales, with the contours scaled down until 95% of the green is 3.3% or
less. None of them uses a tier or a false front. The Old Growth greens average about 138 and use both.

On a new course, split most greens into two or three levels with `green.tier` (a ridge about 1.5 feet high, turned with its
third value) and the swales. The pin sits on one level, and that level is the landing zone: about 8 to 10 yards across.
An approach that lands on another level leaves a long putt up or down the tier. Keep the greens smaller, `rx` and `ry`
about 10 to 12, so the levels stay small. Put a false front (`green.ff`) on the greens where a short approach should roll back
off, and a runoff (`runoff` on the hole, in metres) at the back or side where a long one should run down the bank. Keep the cup at least 4 m from
a tier or false front, because neither is scaled down with the contours.

Check it from the green itself with `_golfputt.js` (local, kept out of git, load it after `_golftest.js`). `greenMap(h)`
lays a 2.5 m grid over the green with the hole's pin. From each point it finds the putt a good reader hits (the line and
pace that would stop dead on the cup) and then strikes it 5% soft and 5% hard. Each point is marked `.` if both leave
under 4 feet, `+` for 4 to 6 feet, `#` for over 6 feet. On a Heronwood green that came out 76% under 4 feet and none over
6, which is what Chris found too easy. On a Murrelet Grove green with a back tier, the pin's level was all under 4 feet
and the other level all over 6. Aim for that: the region round the pin under 4 feet is 20 to 40% of the green, about 8 to
10 yards across, and at least 40% of the green is over 6 feet.

What got there on the Heathland and Georgia greens (2026-10-28): ridges of 1.3 to 1.5 feet were too gentle. Two ridges per
green about 2 feet high (1.4 to 2.0 on the faster Georgia greens), one across the line and one along it, put the pin in a
section about a quarter of the green, e.g. `tier: [[0, 2.1, 0], [2.5, 1.8, 90]]`. Keep the pin at least 4.5 yards from
each ridge: with the pin at [right, back], its distance from a ridge [offset, feet, turn] is
|back × cos(turn) + right × sin(turn) − offset|. On a drivable hole a raised back level can stop a running drive short of
the green, so let the green fall away to the pin's section there. A bunker beside the high corner of a tiered green gets
a face too tall to clear; keep bunkers by the low sections.

Then check the approach (`_golfappr.js`, `approach(h)`). From where a 100% drive finishes, hit the stock approach at the pin's level: it should hold that
level inside a window of a few yards, and the same shot 5% short or long should finish on another level, down a false
front or off the back. `_golfbunk.js` (`bunkHole(h)`) checks every bunker on a hole with a sand wedge and lob wedge from
the centre, the side nearest the pin and the far side.

## Checking a hole

Before a risk/reward hole is done, run shot sweeps through the real hole and confirm three things. The local helpers
`_golftest.js` and `_golfsweep.js` (kept out of git) do this in a `#test` page: `fly()` sends one exact shot (100% or 112%,
a draw or fade as face against path, any aim and wind) through the hole and reports where it stops, and `swXY()` sweeps a
row of aims round a point on the map. A straight 100% shot does not reach the reward. The risky shot (112%, the
draw or fade, the wind it needs) does reach it inside a small aim window, a few degrees, not a wide one. And the misses on
either side of that window land in the penalty the hole promises: water, a drop or a pitch-out. Write the
measured windows into the hole's notes in the README.
