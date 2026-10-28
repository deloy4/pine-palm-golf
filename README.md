# Pine & Palm Golf

A 3D golf game for the browser. Play it at https://deloy4.github.io/pine-palm-golf/ in Chrome on a computer.
There is no build step: `index.html` runs as it is, and GitHub Pages serves the `main` branch, so pushing to
`main` updates the site.

You swing with the mouse. Hold the left button, pull the mouse straight back to set the distance, then push it
forward through where you started. Slant the push to draw or fade the ball and scroll to add or take off loft. On a phone the swing is the same with a
finger, and buttons at the bottom left change the club and loft and turn the aim (hold to turn, tap to nudge); the panels
shrink to the edges of the screen upright or on its side.
Backspin comes from the follow-through: stop short just past where you started for more, keep pushing through
for less. The ball plays back at twice real speed (putts at two and a half times). The camera stays at the tee and
turns to watch the ball until it is about halfway up to its highest point, then moves up to the ball and follows it down
and through the roll. A tap on Space or the mouse speeds the ball up for the rest of the shot, and holding it speeds the
ball up until it is let go. The tracer is a smoke trail about 40 yards long behind the ball (3 yards on a putt) that fades
toward its tail and is gone once the ball stops. `?jumpcam` in the address brings back the camera that stays at the tee
and flies up beside the ball on a tap, and `?nofly` brings back the older full-length tracer. While lining
up a shot, See green (or G) looks down on the green from about 45 degrees with the slope arrows, the flag and a red ring
round the cup drawn larger, and the planned landing spot when it is near the green. When the
ball is in or at the edge of the trees, Drop (or the X key) moves it to the nearest clear spot with an open shot, no nearer
the hole, for a one-stroke penalty.

Off the short grass the lie matters. Rough, pine straw, waste areas, beaches, rocks and bunkers each roll a lie when the
ball stops (in rough it can sit up, sit in the grass or sit down; in sand it can lie clean or plug), and every shot from
there comes out a little different. A wedge cuts through and stays close to its normal distance; a long iron or a wood
gets grabbed and comes out shorter and much less predictable, and it can be caught heavy. A ball sitting up in rough can
come out as a flier, long and with no spin. The projected flight and the carry always show the clean-lie shot, as if from
the fairway and with no wind, so the player has to work out how much the lie and the wind will add or take off.

Elevation works the same way. The projected flight, the carry readout and the club numbers show the carry over level
ground, and the panel shows how far the pin sits above or below the ball. The ball itself flies the real hill: in this
ball flight a 6 iron carries about 10 yards farther to a green 30 feet below and about 11 yards shorter to one 30 feet
above, close to the usual rule of a yard for every 3 feet, so the player has to pick the club for the drop or the climb.

## The courses

All the courses are made up. The first four are in a Florida style with pines, oaks, palms, waste areas and
water; the next four are on the ocean, with cliffs, beaches, coves and surf; the next four are in mountain
forest, with big elevation changes, hillsides, creeks and ranges on the horizon; the next four are on tropical
islands, with lava or coral shores, palms, flowering shrubs and mountains inland; the last four are in the desert,
with saguaros, junipers, dry washes and red rock, where a ball that misses the fairway and its thin band of rough lies in
the desert, on hardpan or in the rocks. Each is par 72, about 7,250 to 7,450
yards, with sharp doglegs whose corners can be carried, holes that bend around water, a drivable par 4, par 5s reachable in
two only over trouble, and fairways that tilt toward hazards.

The Old Growth set is the hard one: Murrelet Grove (California redwoods), Capercaillie Wood (Black Forest spruce), Kiji
Valley (Japanese cedar and maple) and Ptarmigan Pass (the Swiss Alps, 30 to 150 feet of climb or drop on every hole). Its trees are giants, 45 to
70 metres tall, so the woods can't be carried: a drive peaks near 30 metres, and a ball that flies into a giant's crown
always drops. Fairways are about 20 to 24 yards wide and the doglegs turn at 215 to 235 yards, well inside a drive. On
each dogleg two big spruces stand on the straight line from the tee to the far side of the corner, so a straight drive
can't make the turn: a draw or a fade (or a bigger hook or slice) bends round them, or a wood or iron lays up short of
the corner. A curving drive only bows about 7 yards off a straight line (12 for a big hook), which is why the trees sit
on the line rather than relying on the corner alone. The set also has gaps and chutes cut through the woods, split
fairways, false fronts, tiered greens, pot bunkers, raised greens with shaved runoff banks, creek ravines to carry and
blind tee shots, with wind of 6 to 22 mph that holds for the whole hole.

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
| Murrelet Grove, Redwood Course | Giant redwoods, doglegs at 1, 4, 6, 8, 9, 11, 13, 15, 17 and 18 that need a draw or fade past two spruces on the line, a gap in the trees on 2 to a landing pad 258 yards out (a 3 wood) that leaves about 205 to the green, a ten-yard chute on 14 straight to the green 281 yards away, creek ravines on 7 and 11, a stand of redwoods splitting the 5th, raised greens with runoff banks on 3 and 15 | 7,200 |
| Capercaillie Wood, Spruce Course | Black Forest spruce, doglegs at 1, 4, 5, 7, 9, 11, 14, 17 and 18 guarded by spruces on the line, blind crests on 1, 4 and 9, split fairways on 2 and 10, a chute on 6 straight to the green 268 yards away, a gap to a landing pad on 13, creek ravines on 7 and 16, a pond carry on 3 | 7,180 |
| Kiji Valley, Cedar Course | Japanese cedars and red maples, doglegs at 1, 3, 4, 7, 9, 10, 12, 14, 16 and 18, a draw-then-fade 3rd and a fade-then-draw 16th, creek ravines on 2 and 12 and creeks short of the greens on 7 and 18, a gap to a landing pad on 8, a chute on 13 to the green 272 yards away, tiered greens and pot bunkers throughout | 7,175 |
| Ptarmigan Pass, Alpine Course | Swiss Alps with 30 to 150 feet of elevation change on every hole, cliffs above a lake on 4 and 13, a 130-foot drop to a perched green on 3, a 100-foot drop over a tarn on 12, perched greens with runoff banks on 3, 6, 8, 16 and 18, a chute on 7 to the green 285 yards away, a gap to a landing pad on 11 | 7,315 |
| Verdin Springs, Oasis Course | Lakes on most holes, sharp doglegs at 4, 8, 11 and 15, an island fairway at 14, a peninsula green at 12, par 5s at 2 and 13 reachable over water, a finish climbing into the mountains | 7,340 |
| Curlew Links, Links Course | Firm seaside links with no trees: a 112% draw into the neck on the par 5 2nd, a drivable 4th that tilts to the beach, a pond carry to a strip on the par 5 9th, a drivable 13th past a burn, a drivable 14th across the gorse, a hidden strip over the gorse on the par 5 15th, burns that catch a 112% drive on 6 and 18 | 7,338 |
| Gannet Strand, Dunes Course | Big Kerry dunes with holes in the valleys between them, a neck between a burn and four pots on the 2nd, a drivable 5th bending right along the beach, a carry over a dune valley to the far ridge on the 7th, a cape over the dune lake to a green 308 yards away on the 11th, a diagonal burn on the 15th, a split fairway with a strip past a gorse ridge on the 17th | 7,240 |
| Dunlin Sands, Burns Course | Flat Fife links with burns across or beside most holes, a short 2nd with two fairways split by a gorse spine, a carry over a diagonal burn and gorse to a strip on the 5th, a drivable 8th through a gap in a row of pots, a squeeze between the beach and a line of pots on the 11th, a burn at the corner of the 14th, a tiny pot-ringed 13th | 7,208 |
| Skua Head, Cliffs Course | Orkney clifftop links 70 to 80 feet above the sea with geos and coves cut into the cliffs, a drivable 2nd over a cove to a headland green, a geo slanting across the 4th, a squeeze between pots along the cliff on the 8th, a geo across the 10th, a drivable 12th through a neck between two coves, a carry over the headland gorse on the 15th with a cove guarding the green | 7,268 |
| Grouse Hollow, Maple Course | Sugar maples in red and gold on gentle hills, a gap in the trees on 2 to a pad 190 from the green, a drivable 4 tilting into a pond, a corner to cut over the maples on 8, a neck between two stands of maples on 9, a pond and woods to carry on 13 | 7,285 |
| Wood Duck Run, Creek Course | Aspens and maples with a creek or pond on most holes, a drivable 2nd across a corner pond, a pond to carry on 3, a short dogleg on 6 cut over the aspens, a neck beside a pond on 9, a gap through the woods on the long corner of 11 | 7,235 |
| Bobolink Farm, Farm Course | Old farm fields on rolling ground with 20 to 45 feet of climb or drop on most holes, a drivable 3rd from a hilltop tee, a gap to a pad on 5, a long par 4 at 8 bending back on itself with a cut over the maples, a neck between a bunker and a stand on 11, a farm pond to carry on 14 | 7,340 |
| Cardinal Oaks, Oak Course | Big oaks in russet and red on flat ground, lone oaks standing in the fairway on 1, 6, 15 and others, a drivable 2nd past a pond and an oak, a gap to a pad on 5, a square corner cut on 7, a neck between oaks on 10, a pond to carry on 13, a drivable 17th across a corner pond | 7,340 |
| Peregrine Quarry, Granite Course | Grey granite pits 60 to 80 feet deep, the 1st beside a shallower pit; a carry over a pit to a strip on the par 5 2nd and over two pits on the par 5 13th, a drivable 4th whose landing area tilts into a pit, a drivable 8th across a pit, a ledge between two pits on the par 5 9th, a drivable 15th through a gap between two pits | 7,220 |
| Swallow Pit, Limestone Course | Cream limestone benches, tees up to 25 feet above the fairways; a neck between a pit and a stand of trees on the par 5 3rd, a drivable 5th to a green on a point, carries over pits to strips on the par 5 8th and 11th, a drivable 12th round a pit, a drivable 15th across the corner of a diagonal pit | 7,220 |
| Raven Ledge, Pink Granite Course | Pink granite and pines, pits up to 90 feet deep; a drivable 2nd round a pit, a drivable 5th over a narrow pit, a carry to a round pad on the par 5 9th, a slanted ledge between two pits on the par 5 11th, a drivable 14th past a long cut, a ten-yard chute through the pines to the 17th green | 7,210 |
| Kingfisher Cut, Slate Course | A long flooded slate cut that the holes play along and across; a drivable 2nd over the end of the cut, a strip between the cut and bunkers on the par 5 4th, a carry over the cut to a pad on the par 5 9th, a drivable 12th across the cut and a pit, two cuts across the par 5 14th, a drivable 15th to a green on a spit | 7,220 |
| Nightjar Heath, Heath Course | Surrey heath: heather rough, Scots pine and birch, small greens on three or four levels; a 112% draw through the neck between bunkers on the par 5 2nd, a drivable 3rd tilting into a pond, a 112% drive or fade across the pines to the green on the 6th, a 112% draw round the corner of the par 5 8th, a draw past the bunker run on the par 5 12th, a drivable 13th with a pond right, a pond in front of the par 5 17th's green | 7,207 |
| Woodlark Common, Pine Course | Scots pine and birch woods over heather on gentle ground: a gap in the pines to a pad on the par 5 2nd, a drivable 5th tilting into two bunkers, corners to cut over the pines on 8 and 14, a neck between two stands of pines on the par 5 11th, a par 5 17th reachable past a row of bunkers | 7,247 |
| Stonechat Down, Open Heath Course | Open heath with only a few pines, heather everywhere past the fairway, big sandy bunkers and more wind: a drivable 3rd tilting into a big bunker, a valley of deep heather to carry on the par 5 6th, a corner cut over heather and bunkers on 9, a neck between two big bunkers on the par 5 12th, a split-fairway drivable 17th, a par 5 18th reachable through a tilted neck | 7,145 |
| Whinchat Moor, Moor Course | Moorland heath in the Perthshire hills with broom, birch and burns, tees 60 to 120 feet up: a neck beside a burn on the par 5 2nd, a drivable downhill 4th beside the burn, a lochan to carry to a strip on the par 5 7th, a corner cut over a lochan on 10, a neck beside a burn on the par 5 13th, a drivable downhill 17th with a burn down the right | 7,103 |
| Woodlark Common | 20-33% | 51-73% |
| Stonechat Down | 22-29% | 53-77% |
| Whinchat Moor | 21-31% | 60-73% |
| Thrasher Creek, Azalea Course | Augusta-style pines and azaleas on rolling ground with drops of 20 to 60 feet: a gap in the pines on the par 5 2nd to a pad in reach in two, a drivable 3rd beside the creek that tilts toward it, a 112% neck on the uphill par 5 8th, a gap at the corner of the long 11th, a pond carry to a strip on the par 5 13th with the creek in front of the green, a neck on the downhill par 5 15th short of a pond | 7,397 |
| Bobwhite Plantation, Longleaf Course | A flat old quail plantation of longleaf pine and pine straw with sandy waste areas: a drivable 2nd tilting toward a pond, a neck by a waste area on the par 5 3rd, a gap at the corner of the 5th, a pond across the par 5 8th that a 112% drive carries, a gap in the pines on the par 5 11th to a pad, the 13th drivable across the corner over waste and pines, a neck between two waste areas on the par 5 16th | 7,213 |
| Pileated Ridge, Ridge Course | North Georgia hills near Dahlonega: hardwoods, pines and hemlock with redbud and dogwood, mountain laurel, leaf litter, high tees and mountain streams; a canopy gap to a pad on the par 5 2nd, a drivable 5th from the high tee that tilts into the stream, a stream that catches a 112% drive on 4, a 112% drive into the neck on the par 5 8th, a dogleg 10th cut over a ravine pond, a stream carry to the strip on the par 5 11th, a drivable 14th that tilts into a pond | 7,200 |
| Towhee Lake, Lake Course | Pines and azaleas round the coves of a big lake: a cape across a cove on the drivable 2nd, a split fairway over a cove on the par 5 5th, a drivable 7th that tilts into a cove, a 112% drive into the neck by the lake on the par 5 11th, a cove carry to a pad on the par 5 16th, a cove inlet that catches a 112% drive on 18 | 7,208 |

### Measured risk and reward windows

Every risk/reward hole on the Links, Parkland and Quarry courses was checked with shot sweeps in the real hole (no wind,
aims in whole degrees from the line given). 100% means a full stock drive, 112% a full overswing, and a draw or fade is a
face 3° closed or open to the path.

Curlew Links. 2nd: a 100% drive leaves about 315; a 112% draw aimed 6 to 8° right holds the neck and leaves about 258 (a 3
wood runs up); 4 to 5° finds the pots, 9° and wider the right rough. 4th: a 100% drive stops about 50 short and a straight
112% about 30 short; a 112% draw aimed 7 to 9° right finishes on the green, left of that are the pots and the beach. 6th
and 18th: a 100% drive stops short of the burn, a 112% drive runs into it. 9th: aimed at the strip, every 100% drive is in
the pond; a 112% drive holds the strip from 1° left to 2° right and leaves about 135, and a 100% draw aimed 4 to 7° right
holds it and leaves about 155; everything else is gorse or water. 11th: a 100% drive leaves about 293; a 112% draw aimed 6
to 9° right leaves about 240. 13th: a 100% drive stops about 50 short; a 112% draw aimed 7 to 8° right finishes on or at
the edge of the green, with pots and the burn left of it. 14th: every 100% drive across the corner is in the gorse; a 112%
drive finishes on the green from 1° left to 1° right. 15th: every 100% drive across the corner is in the gorse; a 112%
drive holds the strip from 2° left to 1° right and leaves about 135.

The other Links courses (s100 = 100% straight, s112 = 112% straight, draw112 = 112% with a 3° draw):

Gannet Strand
- 2 (par 5 590, neck between a burn on the left and pots on the right from 320): s100 286 out at every aim on the fairway (3 wood
  can't reach); s112 aims -1..+2 263-267 out (aim +1 a pot) — 3 wood reaches; misses left in the burn, right in pots/rough 298+.
- 5 (par 4 330, drivable bending right, beach and sea right, tilt right): s100 22-26 short; s112 aims -2..-1 on the green;
  draw112 +4..+6 on the green. Misses: right pots/beach/water, left gorse.
- 7 (par 5 545, dune valley carry; fairway starts on the far ridge at 285): s100 all in the valley gorse/rough 266-283 out;
  s112 aims -1..+3 (5°) on the ridge 227-228 out. Safe play: iron to the pad at 140-195.
- 11 (par 4 350, cape over the dune lake, green 308 straight across): s100 water at -3..+3, gorse/pots/rough elsewhere;
  s112 aim 0 on the green, ±1 fringe; draw112 +5..+6 on the green. Misses water/gorse/pots.
- 15 (par 4 440, diagonal burn, nearest 335 on the left): s100 short of it 133-141 out; s112 in it at -1..+2.
- 17 (par 5 565, split fairway): main fairway — driver runs into the burn at 304 (s100 water at -3..+1), 3 wood stops short 282
  out. Strip — s100 at it lands in gorse at every aim; s112 -1..+2 (4°) strip 246-252 out; draw112 +4..+6 211-216 out. Misses
  gorse or the burn.

Dunlin Sands
- 2 (par 4 318, two fairways split by a gorse spine to 290): s100 21-29 short down either fairway, gorse 55 out down the middle;
  s112 aims -1..+2 (4°) on the green. Misses pots/rough.
- 5 (par 5 560, diagonal burn then gorse to a strip): s100 burn/gorse at every aim; s112 aim -2 strip 179 out (1°);
  draw112 +5..+6 (2°) strip 129-134 out. Misses burn/gorse.
- 8 (par 4 320, drivable through a gap in a pot row at 300-310): s100 17-27 short (aims -3..0 reach a pot); s112 +1..+2 green;
  draw112 +4..+6 green. Misses pots.
- 11 (par 5 590, squeeze between beach (tilt left) and pots from 318): s100 278-292 out; s112 -2..+1 263-268 out (+2 a pot);
  draw112 +5..+6 231-237 out. Misses left beach/gorse, right pots.
- 14 (par 4 450, burn at the corner 345-359): s100 142-150 out short of it; s112 in it at +1..+3.

Skua Head
- 2 (par 4 318, cove across 243-267 with cliffs): s100 in the cove at every aim; s112 -1..+2 (4°) on the green.
- 4 (par 5 565, geo slanting across at 240-275): s100 in the geo at every aim; s112 -3..+2 237-244 out.
- 8 (par 5 600, squeeze between pots from 320, tilt to the cliff): s100 286-301 out; s112 -1..0 273-275 out (-3..-2 pots);
  draw112 +5..+6 237-239 out (+3..+4 pots).
- 10 (par 4 445, geo slanting across at 320-355): s100 132-136 out short of it; s112 in it at -2..+2.
- 12 (par 4 330, neck between two coves): s100 stops at the neck 23-26 short (aims -1..0), coves either side; s112 aim 0 green
  (1°), everything else in a cove.
- 15 (par 5 545, headland gorse carry to a strip, cove in front of the green): s100 gorse at every aim; s112 -1..+2 (4°) strip
  148-150 out; draw112 +4..+6 113-140 out.

Narrow windows to know about: Dunlin 5 (s112 1°, draw 2°), Skua 12 (s112 1°), Gannet 11 (s112 1° plus fringe either side).

Parkland. Shots: 100% straight, 112% straight, 112% draw (3° closed, path +3). "Reach" means finishing on fairway, first cut or fringe within 255 yards of the pin (a 3 wood runs 263). Misses marked woods mean a drop or a pitch out.

**Grouse Hollow**
- 2 (par 5, gap to pad): 100% in the woods at every aim. 112% straight -2 to +2 (5°), leaves 193. 112% draw +5 to +8 (4°), leaves 172. Misses in the woods.
- 4 (drivable 330): 112% draw +6 to +8 (3°) on the green. 100% stops 47 to 50 short; 112% straight 24 to 30 short. Left misses in the pond, right misses in rough 28 to 32 out.
- 8 (corner cut, 400): 112% draw +5 to +7 (3°) on the green. 112% straight finishes 24 to 49 short; 100% in the woods at every aim.
- 9 (par 5 neck): 112% draw +4 to +7 (4°) leaves 247 to 248. 100% leaves 295, 112% straight 271. Left misses sand or woods, right misses the pond.
- 13 (par 5 over the pond): 112% straight -3 to +2 leaves 169 to 170 (edges at the tree line). 112% draw +3 to +9, cleanest +4 to +7, leaves 146. 100% in the trees past the water at every aim.

**Wood Duck Run**
- 2 (drivable across the corner pond, 350): 112% draw +5 to +7 (and +9) on the green. 100% in the pond from -3 to +3 (aims +4/+5 cut onto the second fairway, 35 to 39 out). 112% straight 28 to 32 short.
- 3 (par 5 over the pond): 112% draw +5 to +8 (4°) leaves 142 to 143; 112% straight only at 0. 100% in the woods at every aim.
- 6 (short dogleg cut, 330): 112% straight 0 to +1 and 112% draw +5 to +8 on the green. 100% finishes 29 to 48 short, in the creek or in the woods.
- 9 (par 5 neck): 112% draw +4 to +7 (4°) leaves 249 to 252. 100% leaves 298, 112% straight 274. Left misses the pond.
- 11 (par 5 gap): 112% straight -3 to +2 (6°) leaves 219 to 231. 112% draw +3 to +8 leaves 195. 100% in the woods at every aim.

**Bobolink Farm**
- 3 (downhill drivable, 350): 112% draw +4 and +6 to +8 on the green. 100% stops 51 short, 112% straight 29 short. Misses left in sand or woods.
- 5 (par 5 gap): 112% straight -2 to +2 leaves 229 to 232 (also +11/+12 onto the second fairway, 246 to 253). 112% draw +5 to +8 leaves 206. 100% in the woods at every aim.
- 8 (long par 4 cut, 440): 112% draw +5 to +7 (3°) on the green. 112% straight and 100% in the woods at every aim.
- 11 (par 5 neck): 112% draw +4 to +8 leaves 250 to 252. 100% leaves 299, 112% straight 275. Misses in sand or woods.
- 14 (par 5 over the farm pond): 112% draw +5 to +7 (3°) leaves 95. 100% in the pond or woods; 112% straight in the woods.

**Cardinal Oaks**
- 2 (drivable 335, pond right, oak left): 112% draw +4 to +6 (3°) on the green. 100% stops 53 short, 112% straight 29 to 31 short. Right misses in the pond.
- 5 (par 5 gap, square corner): 112% straight -1 to 0 leaves 147 to 154. 112% draw +4 to +8 leaves 126. 100% in the woods at every aim.
- 7 (long par 4 cut, 435): 112% draw +5 to +7 (3°) on the green. 112% straight 35 to 62 short or in the woods; 100% in the woods at every aim.
- 10 (par 5 neck): 112% draw +4 to +8 leaves 243 to 246. 100% leaves 292, 112% straight 268. Misses in sand or woods.
- 13 (par 5 over the pond): 112% straight -2 to +2 leaves 255. 112% draw +3 to +8 leaves 229 to 232. 100% in the woods at every aim.
- 17 (drivable across the corner pond, 355): 112% draw +4 to +7 (4°) on the green. 100% in the pond from -4 to +3; 112% straight 23 to 30 short.

Quarry. Shots: 100% straight, 100% draw/fade, 112% straight, 112% draw (path 3° in-to-out, face square), 112% fade. Reward is "on
the green" for the par 4s and "on fairway or first cut, 255 yards or less to the pin" for the par 5s. Every 100% straight
drive misses the reward on every hole. Misses not listed as water finished in rubble or trees (drop) or rough beside the
reward. One sweep result was not repeatable: a 112% draw at -10° on Swallow Pit 5 showed the green once, then rubble
98 yards out when re-flown (a tree deflection); it is left out below.

### Peregrine Quarry (par 72, 7,220 yards)

- Hole 2 (par 5, 555 yds): 100% straight: never; water at -7° to 8°; 100% draw: on fairway in reach in two (255 or less) at 2° to 7° (178-186 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -2° to 2° (165-166 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at 4° to 8° (143-161 yds to the pin); 112% fade: on fairway in reach in two (255 or less) at -9° to -4°, 12° to 14° (170-220 yds to the pin)
- Hole 4 (par 4, 336 yds): 100% straight: never; water at -10° to -7°; 112% straight: never; water at -10° to -5°; 112% draw: on the green at 6° to 8° (4-8 yds to the pin)
- Hole 8 (par 4, 374 yds): 100% straight: never; water at -6° to 7°; 112% straight: on the green at -1° to 0° (8-11 yds to the pin); 112% draw: never; 112% fade: on the green at -7° (11-11 yds to the pin)
- Hole 9 (par 5, 580 yds): 100% straight: never; 112% straight: never; water at -10° to -6°, 6° to 14°; 112% draw: on fairway in reach in two (255 or less) at 4° to 8° (251-252 yds to the pin)
- Hole 13 (par 5, 555 yds): 100% straight: never; water at -7° to 14°; 100% draw: on fairway in reach in two (255 or less) at 2° to 3° (198-207 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -2° to 2° (179-180 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at 4° to 8° (155-173 yds to the pin); 112% fade: on fairway in reach in two (255 or less) at -9° to -4° (184-195 yds to the pin)
- Hole 15 (par 4, 336 yds): 100% straight: never; 112% straight: never; water at -10° to -3°, 2° to 12°; 112% draw: on the green at 5° to 7° (6-11 yds to the pin); 112% fade: never; water at -10°, -5° to 6°

### Swallow Pit (par 72, 7,220 yards)

- Hole 3 (par 5, 580 yds): 100% straight: never; 112% straight: never; water at -10°; 112% draw: on fairway in reach in two (255 or less) at 0° to 5° (248-253 yds to the pin)
- Hole 5 (par 4, 340 yds): 100% straight: never; water at 6° to 14°; 112% straight: never; water at 3° to 14°; 112% draw: on the green at 4° to 7° (3-13 yds to the pin)
- Hole 8 (par 5, 566 yds): 100% straight: never; water at -5° to 14°; 100% fade: never; water at -10° to 9°; 112% straight: on fairway in reach in two (255 or less) at -2° to 2° (170-172 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at -10° to -7°, 4° to 8° (148-185 yds to the pin); 112% fade: on fairway in reach in two (255 or less) at -9° to -4° (175-186 yds to the pin)
- Hole 11 (par 5, 536 yds): 100% straight: never; water at -9° to 4°; 100% draw: on fairway in reach in two (255 or less) at 7° (175-175 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -2° to 2° (171-172 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at 4° to 8° (148-167 yds to the pin); 112% fade: on fairway in reach in two (255 or less) at -9° to -4°, 12° to 14° (176-223 yds to the pin)
- Hole 12 (par 4, 380 yds): 100% straight: never; water at -7° to 7°; 112% straight: on the green at -2° to 2° (2-12 yds to the pin); 112% draw: never; 112% fade: on the green at -8° to -5° (4-10 yds to the pin)
- Hole 15 (par 4, 355 yds): 100% straight: never; water at -3° to 14°; 112% straight: never; 112% draw: on the green at 5° to 7° (4-13 yds to the pin); 112% fade: never

### Raven Ledge (par 72, 7,210 yards)

- Hole 2 (par 4, 390 yds): 100% straight: never; water at -7° to 7°; 112% straight: on the green at -1° to 1° (6-10 yds to the pin); 112% draw: never; 112% fade: never
- Hole 5 (par 4, 322 yds): 100% straight: never; water at -10° to 14°; 112% straight: never; water at -10° to -9°, 11° to 14°; 112% draw: on the green at 4° to 8° (2-13 yds to the pin); 112% fade: never; water at -10° to 14°
- Hole 9 (par 5, 553 yds): 100% straight: never; water at -8° to 8°; 100% draw: on fairway in reach in two (255 or less) at 1° to 2°, 9° (191-196 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -4° to 4° (173-186 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at -10° (187-187 yds to the pin); 112% fade: on fairway in reach in two (255 or less) at -10° to -3° (177-189 yds to the pin)
- Hole 11 (par 5, 582 yds): 100% straight: never; 112% straight: never; water at -7° to -4°; 112% draw: on fairway in reach in two (255 or less) at 7° to 11° (251-254 yds to the pin)
- Hole 14 (par 4, 365 yds): 100% straight: never; water at -5° to 14°; 112% straight: on the green at 0° (11-11 yds to the pin); 112% draw: on the green at 5° to 7° (9-10 yds to the pin); 112% fade: on the green at -7° (11-11 yds to the pin)
- Hole 17 (par 4, 338 yds): 100% straight: never; 112% straight: on the green at 0° to 1° (9-10 yds to the pin); 112% draw: on the green at 5° to 7° (10-13 yds to the pin); 112% fade: on the green at -7° to -6° (10-11 yds to the pin)

### Kingfisher Cut (par 72, 7,220 yards)

- Hole 2 (par 4, 350 yds): 100% straight: never; water at -10° to 0°; 112% straight: never; water at -6° to 0°; 112% draw: on the green at 6° to 7° (4-9 yds to the pin); 112% fade: never; water at -9°
- Hole 4 (par 5, 583 yds): 100% straight: never; water at -10° to -4°; 112% straight: never; water at -10° to -3°; 112% draw: on fairway in reach in two (255 or less) at 5° to 8° (254-255 yds to the pin)
- Hole 9 (par 5, 557 yds): 100% straight: never; water at -10° to 14°; 100% draw: on fairway in reach in two (255 or less) at 2° to 8° (199-223 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -4° to 4° (194-207 yds to the pin); 112% draw: never; 112% fade: on fairway in reach in two (255 or less) at -10° to -3°, 11° to 14° (198-246 yds to the pin)
- Hole 12 (par 4, 395 yds): 100% straight: never; water at -10° to 6°; 112% straight: never; water at -10°; 112% draw: on the green at 4° to 7° (2-13 yds to the pin); 112% fade: never
- Hole 14 (par 5, 541 yds): 100% straight: never; water at -10° to 14°; 100% draw: on fairway in reach in two (255 or less) at 5° to 10° (239-242 yds to the pin); 112% straight: on fairway in reach in two (255 or less) at -1° to 6° (234-250 yds to the pin); 112% draw: on fairway in reach in two (255 or less) at 6° to 11° (212-215 yds to the pin)
- Hole 15 (par 4, 333 yds): 100% straight: never; water at -9° to -4°; 112% straight: never; water at -9° to -3°; 112% draw: on the green at 6° to 8° (5-11 yds to the pin); 112% fade: never; water at -10°

### Heathland and Georgia: measured windows and greens

Same shots as above, no wind, aims in whole degrees from the hole's line (s100 = 100% straight, s112 = 112% straight,
draw112/fade112 = 112% with the face 3° closed or open to the path). Every green was also checked with `greenMap`
(`_golfputt.js`): from each point the putt that would stop dead on the cup is struck 5% soft and 5% hard. Across the 144
greens, 20 to 41% of each green leaves both under 4 feet and 45 to 79% leaves one over 6 feet (Heronwood's 1st, for
comparison: 76% and 0%). From where a safe drive finishes, the iron that holds the pin's section has a carry window of a few
yards (3 to 9 on the holes measured), and the same shot 5% short or long finishes on another level or off the green.

Nightjar Heath
- 2 (par 5 585, neck between bunkers at 300-330): s100 -4..0 fairway leaving 305 (no reach); s112 -3..0 leaving 282;
  draw112 +3..+5 (3°) leaving 257-259 (3 wood); misses in the bunkers or heather.
- 3 (par 4 328, drivable, pond left of the landing area, tilting to it): s100 +1..+3 fairway 47-50 short; draw112 +7 on the
  green (1°), +8 fringe; s112 in the pond; misses in the pond or heather.
- 6 (par 4 325, dogleg right round a stand of pines): s100 +5..+8 fairway 31-39 short round the corner; s112 +8..+11 on the
  green or fringe; fade112 +2..+4 on the green; misses in the pines left, rough right.
- 8 (par 5 580, dogleg left): s100 -2..+6 fairway leaving 293; s112 +1..+4 leaving 268-271; draw112 +6..+8 (3°) leaving 245;
  misses in the pines and heather.
- 12 (par 5 590, bunker run at 300-340): s100 -3..+1 leaving 308; s112 -1..+1 leaving 284-287; draw112 +5..+7 (3°) leaving
  259-260 (3 wood); misses in the bunkers or heather.
- 13 (par 4 322, drivable from a high tee, pond right): s100 -2..0 fairway 37 short, the pond from +4; draw112 +5..+7 on or
  at the edge of the green; misses in the bunkers left, heather or the pond.
- 17 (par 5 575, pond in front of the green): s100 -5..-1 leaving 291, and a 3 wood from there carries the pond but stops
  about 35 short; s112 -4..-1 leaving 268, a 3 wood reaches; draw112 +3..+6 leaving 242, a 5 wood holds the green; a 5 wood
  or 4 iron from 291 is in the pond.

Woodlark Common
- 2 (par 5 560, gap to a pad): 112% straight -2 to +2 (5°) leaves 210-223; 112% draw +4 to +7 leaves 186-220; 112% fade -9 to -5 leaves 214-227. 100% in the woods at every aim. Misses in the woods.
- 5 (drivable 340): 112% draw +4 to +5 (2°) on the green. 100% stops 48 short; 112% straight 27-31 short. Misses: deep heather left, rough and bunkers right.
- 8 (corner cut, 365): 112% straight -1 to +1 (3°) on the green; 112% draw +5, fade -7 also on. 100% stops 33 short at best or in the trees.
- 11 (par 5 580, neck between pine stands): 112% draw +1 to +3 (3°) leaves 253-254. 100% leaves 300, 112% straight 276-278. Misses deep heather.
- 14 (corner cut, 425): 112% draw +4 to +5 (2°) on the green. 100% in the woods or the pine stand short of the green at every aim; 112% straight short of the green in heather/woods.
- 17 (par 5 580, reachable past a bunker row): 112% draw +8 to +11 (4°) leaves 240-242. 100% leaves 287-293, 112% straight 267-270. Misses sand left (+6/+7), rough right.

Stonechat Down
- 3 (drivable 315): 112% straight 0 to +1 (2°) on the green; 112% draw +5 and fade -7 also on. 100% stops 32 short. Misses the big bunker left, deep heather.
- 6 (par 5 565, heather valley carry): 112% straight -1 to +2 (4°) leaves 249-252; 112% draw +4 to +8 (5°) leaves 227-247. 100% in the valley's deep heather at every aim. Safe play: a 6 iron (fairway, 5° window) leaves about 360.
- 9 (corner cut, 360): 112% draw +5 to +6 (2°) on the green. 100% in deep heather on the cut line (best fairway finish 60 out round the corner).
- 12 (par 5 585, neck between two big bunkers): 112% draw +9 to +12 (4°) leaves 246-250. 100% leaves 295-298, 112% straight 272-275. Misses in the bunkers either side.
- 17 (split-fairway drivable, 310): 112% fade -8 to -7 (2°) on the green down the right-hand fairway. 100% on the safe left fairway stops 18-26 short.
- 18 (par 5 560, tilted neck): 112% straight 0 to +1 (2°) leaves 254; 112% draw +5 to +7 (3°) leaves 229-230. 100% leaves 278-280. Misses the big bunker right, deep heather.

Whinchat Moor
- 2 (par 5 565, neck beside a burn): 112% straight +2 leaves 251, 112% draw +8 leaves 225, 112% fade -5 leaves 255 (about 1° each). 100% leaves 274. Misses in the burn right, sand left. Narrow.
- 4 (drivable downhill 335): 112% draw +6 to +7 (2°) on the green. 100% stops 28 short; 112% straight 10-11 short. Misses in the burn left.
- 7 (par 5 560, lochan carry to a strip): 112% straight -2 to +1 (4°) leaves 199-213; 112% fade -9 to -5 (5°) leaves 201-252. 100% in the lochan at every aim on that line.
- 10 (corner cut over a lochan, 370): 112% draw +5 to +7 (3°) on the green. 100% in the lochan, the heather or the woods on the cut line. Safe play: a 6 iron to the corner (4° window).
- 13 (par 5 575, neck beside a burn): 112% draw +5 (1°) leaves 250. 100% leaves 297-299, 112% straight 274. Misses in the burn left. Narrow.
- 17 (drivable downhill 318): 112% straight -1 to 0 (2°) on the green; 112% draw +5 also on. 100% stops 22-29 short. Misses in the burn right.

Thrasher Creek
- 2 (par 5 575, gap to a pad over the corner): aimed at the pad, s100 in the pines at every aim; s112 -3..0 on the pad
  fairway, 1..3 its first cut, leaving 220-228 (3 wood); draw112 in the pines at every aim; misses -4 and +4 in the trees.
- 3 (par 4 312, drivable, creek left, landing tilts left): s100 -1..1 fairway 26-27 short (safe); s112 0 on the green (1°),
  -3..-1 rough short-left, -4 the creek; draw112 +4 and +6 on the green, -3..+3 and +5 the creek.
- 8 (par 5 560 uphill, neck at 310-330): s100 -6..-2 fairway leaving 279-282 (no reach); draw112 +2..+4 fairway leaving
  231-233 (3 wood/5 wood); 0..+1 the bunker, left of that rough and trees.
- 11 (par 4 510, gap at the corner): aimed at the pad, s100 in the trees short of it (pitch out); s112 -2..0 pad leaving
  179-184, draw112 0..+1 pad leaving 165; +1 and wider clips the pines near the tee. The way round (5 wood, 6° window)
  leaves about 247 over the creek.
- 13 (par 5 560, pond inside the corner, strip beyond): aimed at the strip, s100 in the pond at every aim; s112 -1..+2 on
  the strip leaving 220-223 over the creek; draw112 in the trees. Safe: 4 iron or 5 iron to the corner (4.5°+ window).
- 15 (par 5 560 downhill, pond in front of the green): s100 0..+4 fairway leaving 267-269 (no reach); s112 +1..+4 fairway
  leaving 245-246 (3 wood); fade112 -6..-3 leaving 247-254; misses in the pines or rough.

Bobwhite Plantation
- 2 (par 4 318, drivable, pond right, landing tilts right): s100 -2..0 fairway 33-35 short (safe); draw112 +7..+8 on the
  green (+6 fringe, +4..+5 bunker); s112 0 and -1 fairway 12 short; fade112 into the pond.
- 3 (par 5 590, neck by the waste area at 320): s100 -6..-3 fairway leaving 304-306 (no reach); s112 -5..-2 leaving
  279-282 (no reach); draw112 +1..+4 fairway leaving 255-258 (3 wood); -1..0 the waste area.
- 5 (par 4 480, gap at the corner): aimed at the pad, s100 in the trees short of it; s112 -1..+2 pad leaving 146-154;
  fade112 -1..+2 finishes on the second leg 164-175 out. The way round (3 wood, 5.5°) leaves about 220.
- 8 (par 5 530, pond across at 252-274): s100 in the pond at every aim; s112 -2..+1 fairway beyond it leaving 218-220,
  +2 a bunker; safe play is a 4 iron or 5 iron short of the pond (5° window), leaving about 300.
- 11 (par 5 540, gap to a pad over the corner): aimed at the pad, s100 in the trees at every aim; s112 -3..0 pad leaving
  189-191; draw112 +1..+4 pad edge leaving 169-189.
- 13 (par 4 320, drivable across the corner over waste and pines): aimed at the green, s100 in the waste or the pines;
  s112 +1 on the green (1°), -1..0 fairway/fringe 15-17 short; the way round is a 4 iron to the corner (6° window) and a
  wedge of about 95.
- 16 (par 5 580, neck between two waste areas at 330-345): s100 -4..0 fairway leaving 303-304 (no reach); s112 -3..0
  leaving 279-280 (no reach); draw112 +4..+6 fairway leaving 255 (3 wood), +3 the waste area.

Pileated Ridge
- 2 (par 5 565, gap in the hardwoods to a pad on the line at the green): s100 at the pad in the trees at every aim; s112 -2..+1 (4°) on the pad, 207-209 out (a 5 iron/5 wood reaches); misses in the trees. Way round: 3 wood to the corner, 280 out.
- 4 (par 4 445, stream across at 318-330): s100 -5..-2 on the fairway 153-156 out, short of it; s112 in it at -5..-1.
- 5 (par 4 345, drivable from a 48 ft high tee, stream left, landing by the green tilts left): s100 0..+2 fairway 43-45 short (left of that the stream from -4); s112 0..+1 fairway 21-22 short; draw112 +6 on the green (1°), +7 greenside bunker; draws aimed left of +6 hook into the stream.
- 8 (par 5 565, neck between the stream left and a stand of hardwoods right): s100 +1..+5 fairway 281-284 out (three-shotter); s112 +3..+4 (2°) fairway 260-261 out (3 wood); draw112 +9 fairway 235; fade112 -4..-3 fairway 264-265; misses left in the stream from -6..+2.
- 10 (par 4 340, dogleg left round a ravine pond, cleared line at the green): s100 on the cut line in the trees at -5..+1; s112 0 on the green, -1 and +1..+3 fairway 21-25 short (5°); draw112 +4 rough 14 short; safe 5 wood to the corner (-10..-5, 92 out).
- 11 (par 5 545, from a 52 ft high tee, stream crossing diagonally at 250-290): s100 in the stream at -4..+3; s112 -1..+2 (4°) on the strip 227 out (3 wood reaches); draw112 +6..+8 strip 201-202; fade112 -8..-7 strip 229-233. Way round: 5 iron (-3..+2 fairway, 318 out); a 4 iron off the high tee reaches the stream.
- 14 (par 4 330, drivable, pond left of the green with the ground tilting to it): s100 -1..+3 fairway 40-44 short; s112 +1..+3 fairway 17-23 short; draw112 +6 on the green (1°), +7..+8 in the pond.

Narrow windows: 5 and 14 (draw112 1° on the green, both next to water), 8 (draw112 1°).

Towhee Lake
- 2 (par 4 328, cape across a cove, cleared line over the trees to the green): s100 at the green in the cove at -3..+1 (rough 26-31 out right of it at +2..+3); s112 0 on the green (1°), -2..-1 rough 13-14 and +1 fairway 13 by the green; safe 5 wood to the corner (-2.5..+0.5, 75 out).
- 5 (par 5 560, split fairway: the strip over the cove runs at the green): s100 at the strip in the cove at every aim -5..+4; s112 -1..+2 (4°) on the strip 235-236 out (in reach in two); misses in rough/trees or the cove. Main fairway: Dr -1.5..+1.5 (3.5°), 275 out.
- 7 (par 4 335, drivable, landing by the green tilts right into a cove): s100 -4..0 fairway 42-48 short; s112 -3..-1 fairway 19-25 short; draw112 +4..+6 (3°) on the green; fade112 into the cove from -2.
- 11 (par 5 575, neck between the lake right and a stand of pines left): s100 -2..+1 fairway 292 out; s112 -2..0 (3°) fairway 268-269 out (3 wood); draw112 +5..+6 fairway 244 (2°); fade112 -8..-6 fairway 273; lake from +5.
- 16 (par 5 545, cove carry to a pad on the line at the green): s100 in the cove at -5..+4; s112 -2..+1 (4°) on the pad 194-205 out; draw112 +5 pad 171 (1°); misses in the cove or the trees.
- 18 (par 4 460, cove inlet across at 305-318): s100 -3..0 fairway 187-188 out, short of it; s112 in it at -3..+2.

Narrow windows: 2 (s112 1° on the green, near misses finish 13-14 yds from the pin).

The Links set (Scotland, Ireland and Orkney) has no trees. Its fairways are firm, so a drive carries about 264 yards and
runs out to about 306 (a 7 iron runs about 10), the ground rolls in humps and hollows all through the fairways, pot
bunkers sit in the landing areas and round the greens, burns cross the holes, and past a thin band of fescue rough is
gorse: a ball in it is buried, a wedge hacks it out 25 to 75 yards (often still in the gorse), and Drop is offered. Wind
runs 10 to 26 mph. The Parkland set is inland in autumn: fairways lined with maples, oaks and birches in red, orange and
gold, fallen leaves under the trees, ponds with fieldstone walls, and trees standing on the line of the doglegs. The
Quarry set plays across old stone quarries: fairways and greens on ledges between flooded pits with rock walls 30 to 90
feet down to the water, so a miss off a ledge is wet. The Heathland set is inland on sandy heath in
southern England and Perthshire: a fairway 20 to 30 yards wide, then about 10 yards of heather and then deep heather under
Scots pine and birch (a ball in heather comes out about two thirds of its distance, a buried one only hacks out), firm
fairways, big ragged bunkers and small quick greens on three or four levels. The Georgia set plays through tall pines with
azaleas and dogwoods, pine straw under the trees, creeks, ponds and a lake, and very fast greens on several levels. On
both sets each green has a section round the pin, about 8 to 10 yards across, from which a two-putt is easy; from the
rest of the green it isn't.

Before designing a new course, read `COURSE-DESIGN.md`: the risk and reward rules every course follows.

Courses are data in the `COURSES` table near the top of the script. Each hole lists its par and yardage, a
centreline, the green, bunkers, waste areas, water, elevation along the hole and any corner trees. `open` cuts
clearings into the woods ([yards along, yards across, radius]) so the inside of a dogleg can be carried, and `stand` leaves a
clump of trees inside the corridor. `tilt` ([from, to, feet]) tips the ground across the fairway so a ball landing on the
low side runs toward the hazard there (feet fallen across 30 yards, plus to the right). Greenside bunkers are dug deeper than fairway bunkers, with a higher lip. Ocean holes
add `sea`, a list of straight shorelines given by two points along and across the hole, with an optional beach
width; the course settings choose the trees, the scrub colour and the wind. Mountain holes add `side`, how many
feet the hillside climbs about 100 yards off the line of play (plus for the right, minus for the left), and `wl`,
the water level in feet for a creek or pond up in the hills; the course's `range` sets the mountains around it.
Old Growth holes add `alt` ([[yards along, yards across, to yards along, yards across, fairway width, cleared width], ...]),
extra strips cut through the woods: a second fairway, a narrow chute, a round landing pad (both ends the same point), or
with fairway width 0 a gap of rough to play through; `runoff`, metres of bank round a raised green shaved to fairway height;
`green.ff` ([yards, feet]), a false front; `green.tier` ([yards back of centre, feet, turn°]), a ridge between two levels;
and a 6th bunker value of 1 for a deep pot bunker (a lob or sand wedge gets out, a gap wedge doesn't). Keep pot bunkers off
the bank of a raised green, where the face toward the green gets too tall to clear. Their `flora` lists the giants
(`redwood`, `dfir`, `spruce`, `cedar`, each with a `big` version for corners), and `treeTop` keeps the title and intro cameras
above the trees.
Desert courses are mountain courses with `desert: true`: `pal.floor` is `sonoran`, `redrock` or `highdesert`, `flora`
can list `saguaro`, `ocotillo`, `joshua`, `juniper`, `paloverde`, `hardwood` and `palm`, `edgeMix` weighs the plants along
the edge of the rough (`shrub`, `barrel`, `ocotillo`), `lakeC` colours the lakes and `range.mesa` steps the far range into
flat benches and cliffs. A water entry `{ t: 'wash', s0, s1, d0, d1, dep }` is a dry wash, a sandy channel `dep` feet
deep (4 by default) that plays as a waste area.
Any hole can also place things on the map instead of along and across the centreline, which matters on a bent hole
because the centreline is smoothed round its corners: positions are yards right and forward of the tee in the same frame
as `path` (and scale with it). `altXY` takes the same strips as `alt`, `bunkersXY` [x, y, half-length, half-width, turn°,
pot], `standXY` and `openXY` [x, y, radius], `oaksXY` [x, y] for corner trees, and a water entry `{ t: 'pond', x, y, rx,
ry, rot }` is an oval pond (rx along the direction rot°, counterclockwise from straight right).
Links courses add `gorse: true` (the ground past the rough is gorse, named by `pal.straw`, with its own lie), `rumple`
(metres of humps and hollows through the whole hole) and `turf`, which overrides the surfaces for that course only
(`fair`, `cut`, `straw` and so on, the same fields as `SURF`); `pal.fair` and `pal.cut` colour the fairway and first cut.
Parkland courses use `pal.floor: 'park'` (grass with drifted leaves under the trees) and `pal.bank: 'stone'` (fieldstone
pond walls instead of timber). Quarry courses are coast courses with `coves: true`, `quarry: true` (still water, no surf
line), `beach: 0` and no sea: their ponds are the pits, and the land standing well above the water makes the rock walls;
`pal.cliff` colours the rock and `pal.scrub: 'rubble'` the ground past the rough. `lakeC` sets the lake colour on any course.
Heathland courses add `heather: true`: the rough is heather, with its own lies (sitting up, in the heather, buried), and the
ground past it is deep heather (named by `pal.straw`) where the ball is buried more often. From an average lie in heather a
mid iron comes out about two thirds of its distance, and a buried ball only hacks out. `pal.floor: 'heath'` paints heather,
bracken and bare sand under the pines and birches. On any course `green.tier` can be a list of ridges
(`[[yards, feet, turn°], ...]`) for a green on three or four levels, and `turf.green` sets the green speed (a lower `roll`
is faster).
Island courses are ocean courses with a `range` as well, which puts mountains (and an optional volcano, `cone`)
inland behind the far land; `pal.cliff` and `pal.sand` colour the shore rock and the beach.

## Scores

The home screen is one screen: tabs for the terrains (Florida, Ocean, Mountain, Island, Desert, Links, Parkland, Quarry, Heathland, Georgia, Old Growth and the Range) above that terrain's four
courses, and clicking a course opens it in place with its course record, Play for a score, Practice and its leaderboard.
Play for a score starts at the 1st tee and plays all 18 holes once; finishing the 18th opens the scorecard with Post to
leaderboard. Leaving a score round early (Menu, after a check) ends it with no score; the same check offers Restart round, which drops
the round the same way and starts a new one at the 1st tee. Practice opens the 18 holes under
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
birdie or better on all 18 holes across its rounds. Florida is open; each next terrain (Ocean, Mountain, Island, Desert,
Links, Parkland, Quarry, Heathland, Georgia) opens once two courses on the one before have a round at +5 or better, and Verdin Springs also needs a round under par. Old Growth skips the chain: it opens
after score rounds under par on three different courses. Locked courses can't be practised.

## Coins, the shop, hot streaks and challenges

Coins come from the score-round counts the same way XP does, so rounds played before coins existed count too: 2 a hole,
3 a par, 10 a birdie, 25 an eagle, 60 an albatross, 100 a hole in one, 10 a chip-in, 20 a finished round and 40 a round
under par. Bonuses go into the `coin_bonus` count and spending into `coins_spent`. Coins buy looks only, and nothing in
the shop changes a shot: ball colours, tracer colours (fire and rainbow colour the line along its length), outfits,
flags and celebrations. Each group's first item is free. Outfits recolour the Mixamo golfer's texture: its navy pixels
(shirt and cap) and khaki pixels (trousers) take the new colours and keep their own light and shade. Celebrations play
at the cup when the ball drops for par or better, in any mode. Progress carries `own` (bought, the first purchase
stands), `eq` (worn, the latest choice wins) and `done` (tasks and weekly bonuses already paid, dropped after 60 days),
and `golf_push` merges them like the rest.

A hot streak is a birdie or better on three holes in a row in a score round. It lights the badge beside the hole card,
pays 30 coins, then 40, 50 and so on for each hole it runs on, and counts toward the Hot streak achievement and the
longest-streak best. Like everything else it is paid only when the round is finished.

Three daily tasks (one easy at 25 coins, one middling at 40, one hard at 70) come from the date, the same for everyone,
and each is done inside one finished score round. Days and weeks run on Mountain time, and weeks start Sunday.

The challenges screen (Challenges on the home screen) has four boards, all picked in the database from the date
(`golf_pick`) so everyone plays the same holes. The daily hole is any hole on any course; the first try of the day
counts from its first shot, so leaving partway ends it with no score, and it pays 5 to 80 coins by the score. The
course of the week counts each player's best finished score round there that week; the first one finished pays 50
coins, and that course can be played for a score that week even where it is still locked. Closest to the pin (a par 3,
must finish on the green) and the long drive (a par 5, must finish in the fairway or first cut) are one tee shot a
try, as many tries as you like, best one counts, 20 coins for the first entry each week. The top three win 50, 30 and
20 coins on each daily hole and 150, 100 and 60 on each weekly board, paid the next time they open the game
(`golf_claim_prizes`, inside `golf_challenges`). Challenges can be played on locked courses; entering the boards needs
sign-in. Tables: `golf_courses` (ids and pars, copied from the game for the picks), `golf_entries`, `golf_claims`;
functions `golf_challenges(p_token)` and `golf_entry(p_token, kind, course, hole, value)`. If a course's holes or pars
change in the game, update `golf_courses` too. Its `since` column keeps a course out of the picks for any day or week
before that date, so new courses (the Old Growth four, since 2026-10-25) join at the start of a week without changing a
pick that is already being played.

## Next build: achievement pop-ups and player leaderboards

Achievement pop-ups are for the player, mid-round, so they know the moment they've earned one. When a shot earns an
achievement, a small pop-up slides in at the top of the screen with its name and one line under it, holds about three
seconds with a short sound, and queues behind any other pop-up. Because only finished score rounds count, it says the
achievement counts when the round is finished; the card after the 18th still lists everything saved, and a round ended
early saves none of it. Only achievements pop up; personal bests stay on the last card. Other players don't see anyone's
achievements. The news is already collected per round (`G.round.news` through `newsFor`), so the pop-up hooks in there.

Player leaderboards: one board with tabs, one tab per stat, signed-in players only. Tabs: most XP (with level), lowest
handicap (players with at least 3 finished rounds), longest drive, longest putt holed, and the longest holed from the
fringe, fairway, rough, a bunker and anywhere else (the BESTS list). Each row shows the player and the value, and the
best-distance tabs also show the course, hole and date. It opens from the home screen beside the player's name and from
the profile. XP and handicap should be worked out in the database from golf_progress and golf_rounds (the same XP table
and handicap rules as the game, with golf_ratings), so every player is ranked the same way; the distances come from
golf_progress.recs. One new `golf_board(p_stat)` function returning the top rows plus the signed-in player's own place
would cover every tab.

## The golfer

The golfer is a Mixamo character with Mixamo's drive, chip and putt animations, converted to `golfer.glb`.
Mixamo content may be used in games but not handed out as standalone files, so don't reuse `golfer.glb`
or the files in `characters/` outside this game.

The shop's Golfers tab sells 13 more Mixamo characters at 2,500, 3,500 and 5,000 coins, priced so one takes several
hours of play (a quick player earns about 500 to 700 coins an hour with bonuses). Each is `characters/<name>.glb` plus a
shop picture `characters/<name>.png`, loaded the first time it is worn and kept for the session. They were converted
from the Mixamo FBX downloads in headless Chrome: extra copies of the skeleton that some exports nest inside it were
merged into one, textures shrunk to 1024 or 2048, and the classic golfer's drive, chip and putt clips retargeted onto
each skeleton (each bone turns by the same world-space amount from its T-pose, and hip travel scales with hip height).
Heights are kept between 1.5 and 1.95 m. Characters without finger bones get knuckle markers named like the bones,
so the club and the right-hand grip work the same. Outfits recolour the classic golfer only. The claude.ai artifact
loads each as base64 text (`.glb.txt`, gitignored), like `golfer.glb.txt`. The `golf_push` function accepts
`golfer` as a worn slot (migration `golf_push_golfer_slot`).
