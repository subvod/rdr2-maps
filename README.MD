# rdr2-maps

*A collection of maps showing locations of places to sit, enemy encounters, and rare animals. Tested and validated in single player only. This is not intended for use in RDO.*

## Table of Contents

[Overview](#overview)
<br>&emsp;[Map Key/Legend](#map-keylegend)
<br>&emsp;[Some Notes](#some-notes)
<br>&emsp;[Time Frames](#time-frames)
<br>&emsp;[Rival Gangs](#rival-gangs)
<br>[Animal Locations](#animal-locations)
<br>&emsp;[Western Bull Moose](#western-bull-moose)
<br>&emsp;[Panther](#panther)
<br>&emsp;[Horned Owl](#horned-owl)
<br>&emsp;[Timber Wolf](#timber-wolf)
<br>&emsp;[Cougar](#cougar)
<br>&emsp;[Grizzly Bear](#grizzly-bear)
<br>&emsp;[Little Brown Bat](#little-brown-bat)
<br>&emsp;[Birds](#birds)
<br>[Extended Information](#extended-information)
<br>&emsp;[Testing Procedures](#testing-procedures)
<br>&emsp;[Release Format](#release-format)
<br>&emsp;[Map References](#map-references)
<br>&emsp;[Programs Used](#programs-used)

## Overview

For release format information, see [Release Format](#release-format).

### Map Key/Legend

*Markers/Blips:*

Color | Marker Type
:-- | ---
Solid Red | Enemy Hideout
Hollow Red | Static Spawn<br>Perched Bird<br>Enemy Campsite
Hollow Blue | Animal Random Encounter<br>Enemy Random Encounter<br>Flying Bird

*Locations:*

Abbreviation | State | Regions
:- | -- | --
AM | Ambarino | Grizzlies West<br>Grizzlies East
NH | New Hanover | Heartlands<br>Cumberland Forest<br>Roanoke Ridge
LE | Lemoyne | Scarlett Meadows<br>Bayou Nwa<br>Bluewater Marsh
WE | West Elizabeth | Big Valley<br>Great Plains<br>Tall Trees
NA | New Austin | Hennigan's Stead<br>Cholla Springs<br>Rio Bravo<br>Gaptooth Ridge

### Some Notes

- Text within quotes, for example `"Willard's Rest"`, signifies text on the overworld (pause menu) map. Actual, in-game locations are noted in bold and not in quotes or a code block, as such: **Willard's Rest**. When describing placement relative to individual letters, the associated text will be in quotes and the individual letter(s) mentioned will be bolded. For example: west edge of the 'a' in "Will**a**rd's Rest".
- All reference locations (nearby plants, landmarks, etc) used are those which are the closest to where the animal was spotted. I try not to be vague, like "large rock next to the mountain". Some spawnpoints were a ways away from notable locations, and in those cases I've noted only landmarks and/or plants nearest to the spawnpoint as well as the animal's location relative to them.
- Random encounters seem to appear more frequently if you reload in a nearby location or spend a great amount of time in the general vicinity. This includes all random encounters.
- The chace of random encounters does not change at any point if story mode, contrary to what I suspected. In `Simple Pleasures`, **Abe** says something I feel leans towards this being an actual mechanic put into the game for post-story play: "It’s changed. Rich fellers are coming in and buying everything… the ranches… but… well, it ain’t as wild as it once were, at least." [[Citation.]](#quotes) But, after extensive testing, random encounters are just as random regardless of story progression.
- It is possible to (apparently) increase the likelihood of random encounter spawning: hitch your horse and rest (kneel) a ways away from the point where whatever you're looking for is meant to spawn. Go do something else as time passes. I give at least six in-game hours, horse hitched and me kneeling. After that short while, head towards the location. This is how I get the dodgy animal encounters to spawn more frequently.

### Time Frames

Span | Effect
:--- | ---
06:00-16:00 | Daytime
16:00-06:00 | Night
05:00-21:00 | Miscellaneous birds flying overhead.

Random encounters don't seem to be tied to a specific time span. I've seen a Grizzly at **Barrow Lagoon** right at 02:00, Cougar attacking NPCs on the **Kamassa River** 'round the clock, and Rams headbutting (east of the **Big Valley Trapper**) at midnight. Some seem more common than others, primarily Rams/Bucks headbutting. Those I see way more during the day. Just noting I have seen just about every random encounter at both night and day at least once. I know for sure I've seen them all during the day, so if you're out for an adventure, best go with daytime.

Animal(s) | Description
:--- | ---
Cougar<br>Deer | Cougar stalks and attacks Deer.
Grizzly Bear<br>Gray Wolf | Grizzly eating Deer carcass. Wolves attempt to overpower the Grizzly.
Western Bull Moose | Only occurs at **Lake Isabella**, **Barrow Lagoon**, and **Cairn Lake**.<br>Moose is slipping on ice while attempting to stand upright.
Hawk/Eagle/Owl<br>Fish/Snake/Rabbit/Rat | Bird dives and catches random fish/snake (over water) or random small mammal/snake (on land).
Whitetail Buck | Two Bucks (one dead) with interlocked horns. Live Buck cannot escape.
Whitetail Buck | Two Bucks pushing each other around.
Bighorn Ram | Two Rams headbutt each other.
American Bison | One Bison headbutts another.
Grizzly Bear | Scratching itself on a tree trunk.
Grizzly Bear<br>Sockeye Salmon | Grizzly catches and eats Salmon.
Fox | Stalks and pounces on prey beneath snow. Only occurs in northwestern snowy regions.

## Rival Gangs

- O'Driscolls and Laramies share some of the same random encounter locations.
- O'Driscolls are not meant to be present in the Epilogue. However two can be found stumbling out of Smithfields (Valentine, Heartlands, NH) at night. I also recall a video of a glitched train robbery random event southwest of Armadillo. The event is meant to involve Del Lobos, but due to some fluke it ended up being O'Driscolls. I have seen the former myself, but not the latter.
- The gang around Saint Denis are goons serving **Guido Martelli** (as per **Charles** during `Bare Knuckle Friendships`). [[Citation.]](#quotes) They don't have a known hideout, but are localized to parts of Saint Denis and appear in only random encounters.
- Lemoyne Raiders can be found in **Saint Denis** (Bayou Nwa, LE), but only during random encounters. They can be found at the same spots **Martelli's Men** stand at, but between the two is up to RNG. So far, I've run into Raiders standing around only twice. Also encountered them throwing Fire Bottles at a building in the southwest side of **Saint Denis**.

NAME | LOCAL AREA(S)
:--- | ---
O'Driscoll Boys | Big Valley, WE<br>Heartlands, NH<br>Cumberland Forest, NH
Lemoyne Raiders | Scarlett Meadows, LE<br>Saint Denis, Bayou Nwa, LE
Murfree Brood | Roanoke Ridge, NH
Laramie Boys | Big Valley, WE (Epilogue)
Skinner Brothers | Tall Trees, WE (Epilogue)
Del Lobos | Gaptooth Ridge, NA<br>Cholla Springs, NA<br>Rio Bravo, NA<br>Hennigan's Stead, NA
Night Folk | Lagras, Bayou Nwa, LE<br>Lakay, Bayou Nwa, LE
Martelli's Men | Saint Denis, Bayou Nwa, LE

## Animal Locations

### Western Bull Moose / Western Moose

*Primarily diurnal. Three coats: dark brown (almost black), rust brown (almost orange), and a gray-brown. Pelts yielded by each are incorrect. Example, a rust brown bull yields a pelt that should have come from a gray-brown bull. Possibly associated with dodgy spawns.*

**NOTE:** The most reliable spawns from my experience: Witches Cauldron (OOB spawns), Tall Trees (second 'L'). They're 24-hour spawn points and allow all coats and both genders to spawn. Every other static spawn may as well be considered a random encounter given how rarely even I've come across them.

**NOTE:** Unsure if a glitch, but every bull I run across is rust-brown and every cow I come across is gray-brown. The only places I've been able to get alternative coats of each are: second 'L' in "TAL**L** TREES" and both OOB spawns at **Witches Cauldron, Grizzlies East, AM**.

**NOTE:** Random encounters include: swimming across bodies of water being chased by lone wolf, attempting to stand up on ice.

**NOTE:** If you spend enough time close by, you can get two moose to spawn on the west side of **Lake Isabella**. It's happened to me only once (using RampageTrainer's time lapse feature), so quite rare but possible nonetheless.

- Colter, Grizzlies West, AM (atop small cliff on southeast side of road running northeast out of **Colter**; 06:27, 14:41)
- Lake Isabella, Grizzlies West, AM (beside path on west side of **Lake Isabella**; unaffected by **White Arabian** presence; unaffected by playing wolves random encounter; 09:13, 15:32, 18:40)
- Lake Isabella, Grizzlies West, AM (laying on ice northwest side of **Lake Isabella**; southeast of destroyed cabin; just some paces away from the spawn described above; 06:24)
- Lake Isabella, Grizzlies West, AM (chased by wolf across northwestern **Lake Isabella**; swims to northern shore just southeast of waterfall; 17:45)
- Cairn Lake, Grizzlies West, AM (laying on ice in center of **Cairn Lake**; 06:55, 16:32, 19:27)
- Barrow Lagoon, Grizzlies West, AM (laying on ice southeast side of lagoon; 08:20, 10:45)
- Window Rock, Grizzlies West, AM (west side of train tracks atop cliff overlooking trestle bridge southwest of **Window Rock**; southwest of the trestle bridge itself; dead west of "Dodd's Bluff"; dead south of "Chez Porter"; northeast of dreamcatcher)
- Calumet Ravine, Grizzlies East, AM (west shore of lake next to junctions running east out of **Wapiti Indian Reservation**)
- Calumet Ravine, Grizzlies East, AM (swimming west across the south side of the lake being chased by wolf; directly in line with junction east of **Wapiti**; 14:45)
- Fort Wallace, Cumberland Forest, NH (east of **Fort Wallace**; in trees on west side of road at first junction south of **Bacchus Station**; 10:17-15:01)
- Witches Cauldron, Grizzlies East, AM (west of **Witches Cauldron**; between 'I' and 'N' in "AMBAR**IN**O"; northeast of junction by **Strange Statues**; OOB, but can be lured with bait or by rolling the dice spooking it; alternative coats spawn here; 24-hour)
- Witches Cauldron, Grizzlies East, AM (same as above, but about 100m east-southeast; the spawn is far enough out that the moose doesn't move for anything or anyone; inaccessible from anywhere around, but you can shoot it from the mountain across the path; unknown if nearby OOB access is possible; 24-hour)
- O'Creagh's Run, Grizzlies East, AM (east shoreline of lake; just south of **Veteran's Homestead**; 15 paces west of Alaskan Ginseng plant; to the east of "O'Creagh's" in "**O'Creagh's** Run"; 14:00-17:00)
- O'Creagh's Run, Grizzlies East, AM (near north shoreline of lake; swims south in line with "Cr" in "O'**Cr**eagh's Run" to northeast edge of western peninsula)
- Fairvale Shanty, Grizzlies East, AM (in grass on south side of road; southwest of **Fairvale Shanty**; sleep until morning at **The Loft**; 06:49, 12:32)
- Willard's Rest, Roanoke Ridge, NH (inside 3-way junction just southeast of "Rest" in "Willard's **Rest**"; north side of train tracks; 07:48, 13:15, 18:38)
- Brandywine Drop, Roanoke Ridge, NH (east side of river; edge of first cliff up from river at waterfall; west of first 'R' in "**R**OANOKE RIDGE"; 08:15)
- Deer Cottage, Roanoke Ridge, NH (west of 'A' in "RO**A**NOKE RIDGE"; inside double junctions; 10:55)
- Viking Tomb, Roanoke Ridge, NH (northern shoreline of **Kamassa River**; southwest of **Viking Tomb**; just below moose map icon; 07:01)
- Cattail Pond, Grizzlies West, AM (northeast shore of **Cattail Pond** on path which **Beartooth Beck** flows over; 19:05)
- Cumberland Falls, Heartlands, NH (east shore between 'o' and 't' in "Dak**ot**a River"; across from where **Little Creek River** feeds in; southwest of **Downes Ranch**; 11:15)
- Cumberland Falls, Heartlands, NH (island southwest of 'R' in "Dakota **R**iver"; so far this has been exclusively cow moose; 08:15, 09:42; 12:50)
- Wallace Station, Big Valley, WE (east-southeast of the station; hanging over the path closest to the west side of the **Dakota River**; 06:28, 09:12, 15:15)
- Painted Sky, Big Valley, WE (southern shore of **Dakota River** next to 4 Wild Mint plants; north of **Painted Sky**; below **Burdock Root** map icon)
- Owanjila, Big Valley, WE (chased by wolf swimming across **Owanjila**; swims to northeastern peninsula with 1 **Burdock Root**; 11:45, 17:20)
- Owanjila, Big Valley, WE (chased by wolf swimming across **Owanjila**; swims to southern shore with 1 **Burdock Root**; 07:25, 08:45)
- Fort Riggs, Big Valley, WE (southwest of junction coming from the **Strawberry Stable**; 10 or so paces southeast of boar map icon; 14:01)
- Nekoti Rock, Tall Trees, WE (west side of river; northwest of 'U' in "**U**pper Montana River"; south side of path that crosses the river north of the 'U'; on the edge of a **Loon** map icon)
- Evelyn Miller Camp, Tall Trees, WE (directly east of second 'L' in "TAL**L** TREES"; next to a **Lady Slipper Orchid**; alternative coats spawn here; 24-hour)
- Bear Claw, Tall Trees, WE (second 'E' in "TALL TRE**E**S"; occasionally a random NPC campsite spawns 20m away which seems to disable the moose spawn, if otherwise I never see both of them at the same time)
- Aurora Basin, Tall Trees, WE (between two groups of Burdock Root on the northwest side of **Aurora Basin**; northeast of Skinner Brothers campsite which, if present, will disable moose spawn)
- Aurora Basin, Tall Trees, WE (out-of-bounds atop small cliff on the southwest end of **Aurora Basin**; west side of **Lower Montana River**; may sometimes fall backwards and remain out-of-bounds; draw it out with Herbivore Bait like with the OOB Ambarino moose; 06:00)

### Panther

*Primarily nocturnal. Three coats: two of the ordinary Panther and one of the Florida Panther. All are relatively similar, while the Florida panther has a paler coat than the regular Panther.*

**NOTE:** All coats of the **Panther** and **Florida Panther** spawn at both **Old Harry Fen** and (north of) **Lakay**.

- Old Harry Fen, Scarlett Meadows, LE (two spawns close together; southeast of **Old Harry Fen**; southwest of tri-junction; 24-hour)
- Lakay, Bayou Nwa, LE (two spawns close together; eastern bank of **Kamassa River**; sleeping at water's edge northeast of **Lakay**; 22:00-04:00)

### Horned Owl

*Primarily nocturnal. Three coats: Californian (rust brown), Coastal (brown gray), and Great (gray white).*

Owls seem to share many (if not all) of the same perch locations as Hawks and Eagles. However owls' spawn rate is apparently drastically lower and they only come out at night.

Coastal and Great variants can be found across the entire map despite name implications. I've found Coastals as far north as **Cairn Lake** (Grizzlies West, AM) and as far south as **Lake Don Julio** (Rio Bravo, NA). Owls in **New Austin** are usually Californians, but all three coats can spawn in the entire state.

As far as I can tell, the Californian spawns only south of the **Upper Montana River** until I'm proven otherwise. It is possible to study, kill, and pluck one as Arthur. There is an in-flight spawn north of Blackwater which Owls start from, then have a chance of taking a route headed north in which they fly over both the **Upper Montana River** and **Lone Mule Stead**. I have never seen a Californian perched atop Lone Mule, though. Some players have noted finding it in the marsh flats around **Canebreak Manor** (Bluewater Marsh, LE), but I have yet to see it anywhere north of the **Upper Montana River**.

According to GTABase, the areas with the highest concentration of Owl spawns are (highest to lowest): Tall Trees, slightly north of Strawberry, the whole stretch of the **Little Creek River** (from **Hanging Dog Ranch** to **Sheperd's Rise**), **Cumberland Falls**, the **Trading Post** (point of interest located northwest of **Gill's Landing**), and the entirety of **Cumberland Forest**. I can verify **Tall Trees** is the best for Owl hunting in general, but pre-Epilogue I've killed plenty of Great Horned and Coastals around **Fort Wallace** (Cumberland Forest, NH), **Cumberland Falls** (Cumberland Forest, NH) and down that section of the **Dakota River**, as well as a ton around **Canebreak Manor** (Bluewater Marsh, LE).

- Emerald Ranch, Heartlands, NH (perched in the south window of the barn where **Seamus** runs his **Fence**)
- Guthrie Farm, Heartlands, NH (perched atop the southeast house)
- Strawberry, Big Valley, WE (southwest of Strawberry; perched in tree east of first 'p' in "U**p**per Montana River")
- Chez Porter, Grizzlies West, AM (perched on a wooden bridge south of the cabins at **Chez Porter**)
- Fairvale Shanty, Grizzlies East, AM (perched atop a rock directly south of the shanty; north side of road)
- Cumberland Falls, Big Valley, WE (perched west cliffside)
- Elysian Pool, Roanoke Ridge, NH (perched atop dead tree in pond)
- Canebreak Manor, Bluewater Marsh, LE (flying over the entire area of marsh flats to the north)
- Flat Iron Lake, Scarlett Meadows, LE (small southernmost island; west of Braitewaite Manor)
- Flat Iron Lake, Scarlett Meadows, LE (largest island with beached shipwreck; west of Braitewaite Manor)
- Lone Mule Stead, Big Valley, WE (perched atop **Lone Mule Stead**)
- Tanner's Reach, Tall Trees, WE (perched atop chimney; spawns both before and after **Evelyn Miller** stranger missions)
- Bear Claw, Tall Trees, WE (perched atop southwest cabin)
- Bear Claw, Tall Trees, WE (perched atop northeast cabin)
- Bear Claw, Tall Trees, WE (perched atop southeast cabin)
- Bear Claw, Tall Trees, WE (perched on cliff west of cabins)
- Coots Chapel, Cholla Springs, NA (perched atop chapel)
- Coots Chapel, Cholla Springs, NA (perched atop cactus by front entrance)
- Two Crows, Cholla Springs, NA (perched atop wagon)
- Ridgewood Farm, Cholla Springs, NA (perched atop north barn above front doors)
- Silent Stead, Gaptooth Ridge, NA (perched atop cabin above front door)

- shipwreck islands (atop mast)
- shipwreck islands (atop dead tree)
- elysian pool (atop dead tree)
- aurora basin (atop cliff lakeside)
- aurora basin (atop junction sign)
- aurora basin (atop cliff southeast of lake)

### Timber Wolf

*Primarily nocturnal. Very much localized to **Cotorra Springs, Grizzlies West, AM** and the entirety of **Cumberland Forest, NH**, but can be found in a few places outside of its main habitat. On those fringe locations, every Timber I've encountered was in a team of two. Wolf ambush locations in **Grizzlies West, AM**, **Grizzlies East, AM**, and **Cumberland Forest, NH** seem to randomly spawn either Timbers or Grays. All wolf spawn locations outside of those areas have yielded nothing but Grays.*

- Cairn Lake, Grizzlies West, AM (south side of path; west of lake)
- Lake Isabella, Grizzlies West, AM (west side of path; north of lake)
- Barrow Lagoon, Grizzlies West, AM (west side of path; south of lagoon)
- Cotorra Springs, Grizzlies East, AM (east side of easternmost path aside hot springs)
- Veteran's Homestead, Grizzlies East, AM (peninsula south of cabin)
- Fairvale Shanty, Grizzlies East, AM (south side of road atop hill)

### Cougar

*Primarily nocturnal, but some spawn during the day. Four coats: orange/tan, light brown/tan (almost like buck pelt), gray (very similar to white, especially in moonlight), and white (mission-specific). Aside from random encounters, hotspots are northeast **Roanoke Ridge, NH** (mainly east of the **Kamassa River**) and north of **Ridgewood Farm** (Cholla Springs, NA).*

**NOTE:** The rare white cougar can only be found during `Money Lending and Other Sins IV` while hunting it with **Winton Holmes**. The gray coat can be found in the wild at random, and looks very much like a white cougar especially in the moonlight.

- Pronghorn Ranch, Big Valley, WE (north side of path north of last 'h' in "Pronghorn Ranc**h**")
- Valley View, Big Valley, WE (attacking deer; south of last 'e' in "Little Creek Riv**e**r"; 23:05)
- Black Bone Forest, Big Valley, WE (creek bank feeding into **Owanjila**; west of **Native Burial**; between path and creek)
- Black Bone Forest, Big Valley, WE (southeast side of path; northwest of **Native Burial**; 07:15)
- Doverhill, Roanoke Ridge, NH (spawns on path on west bank of **Kamassa River**; north of train tracks; creeps up to NPC campsite)
- Roanoke Valley, Roanoke Ridge, NH (there are a ton of spawns between **Black Balsan Rise** and **Doverhill**; fewer spawns west of the **Kamassa River**)
- Cochinay, Tall Trees, WE (northwest of first 'T' in "**T**ALL TREES"; 24-hour)
- Beecher's Hope, Great Plains, WE (east of 'G' in "**G**REAT PLAINS")
- Quaker's Cove, Great Plains, WE (between 'N' and 'S' in "GREAT PLAI**NS**")
- Ridgewood Farm, Cholla Springs, NA (north of **Ridgewood Farm**; from southeast of **Rathskeller Fork** to east of **Pleasance House**; there's a ton of spawns between 'C' and second 'L' in "**C**HOL**L**A SPRINGS")
- Rathskeller Fork, Gaptooth Ridge, NA (south of **Rathskeller**; northeast corner of junctions north of 'G' in "GAPTOOTH RID**G**E"; west of rabbit map icon)
- Plainview, Rio Bravo, NA (southwest of **Plainview**; in land depression on north side of path beyond junctions located west of **Plainview**; north-northeast of last 'R' in "SAN LUIS RIVE**R**"; at the base of a rocky hill)
- Benedict Point, Rio Bravo, NA (dead west of **Solomon's Folly**; dead south of the 'i' in "Benedict Po**i**nt"; 15:15)

### Grizzly Bear

*Primarily diurnal, but some spawn at night.*

**NOTE:** Unique encounter at **Vetter's Echo** (Big Valley, WE) happens only once per game save.

- Barrow Lagoon, Grizzlies West, AM (north of 'a' in "L**a**goon"; eating deer carcass, 10:40, 13:25)
- Barrow Lagoon, Grizzlies West, AM (between 'o' and 'n' in "Lago**on**"; eating deer carcass, 09:38, 10:32, 16:15)
- Cattail Pond, Grizzlies West, AM (just east of the pond; eating deer carcass)
- Cattail Pond, Grizzlies West, AM (southeast of pond; south of train tracks near cliff edge and **Alaskan Ginseng** growing on dead brush patch; 13:45)
- Cotorra Springs, Grizzlies East, AM (south of hot springs)
- Fairvale Shanty, Grizzlies East, AM (in small bunch of trees 15 paces south of shanty)
- O'Creagh's Run, Grizzlies East, AM (west shore; eating deer carcass)
- O'Creagh's Run, Grizzlies East, AM (north shore; catching salmon)
- Hanging Dog Ranch, Big Valley, WE (in trees on north side of paths coming from the ranch)
- Vetter's Echo, Big Valley, WE (unique encounter; inside the cabin upon first entry; does not respawn after killing it once)
- Sheperds Rise, Big Valley, WE (streamside northwest of cabin; catching salmon)
- Wallace Station, Big Valley, WE (island west-northwest of 'R' in "Little Creek **R**iver"; catching salmon)
- Wallace Station, Big Valley, WE (unique encounter; inside dinosaur bone cave)
- Wallace Station, Big Valley, WE (there's at least four spawn locations in close proximity between **Watson's Cabin** and **Wallace Station**; all of which are south of the dinosaur bone cave and reasonably close to the old chimney; I've killed three grizzlies in five minutes here)
- Wallace Station, Big Valley, WE (north of the second 'L' in "WAL**L**ACE")
- Watson's Cabin, Big Valley, WE (south shore of the creek; north of 'R' in "Little Creek **R**iver"
- Pronghorn Ranch, Big Valley, WE (south of 'W' in "**W**EST ELIZABETH")
- Black Bone Forest, Big Valley, WE (south-southeast of **Trapper**; just northwest of path diverge from creek; 22:00)
- Nekoti Rock, Tall Trees, WE (standing in the **Upper Montana River** towards the west bank; east of **Nekoti Rock**; west of second 'n' in "Upper Monta**n**a River")
- Bear Claw, Tall Trees, WE (northwest of **Bear Claw**; second 'E' in "TALL TRE**E**S"; snooping around NPC campsite)
- Bear Claw, Tall Trees, WE (west of **Bear Claw**; sitting near cliff edge facing **Lower Montana River**)
- Bear Claw, Tall Trees, WE (south of **Bear Claw**)
- Aurora Basin, Tall Trees, WE (eating deer carcass on northeastern peninsula; 15:15)
- Aurora Basin, Tall Trees, WE (catching salmon on east shore)

### Little Brown Bat

*Solely nocturnal and common across Lemoyne, but can be found in only certain locations outside of Lemoyne.*

- Mount Shann, Big Valley, WE (cave mouth just south of 'U' in "MO**U**NT SHANN"; same cave **Winton Holmes** and the player travel to during `Money Lending and Other Sins IV`)
- Flattened Cabin, Grizzlies East, AM (inside the cabin at **Moonstone Pond**; tons of them if you approach shortly after 18:00)
- Wild Man's Cave, Roanoke Ridge, NH (perched on ceiling of cave entrance)
- Elysian Pool, Roanoke Ridge, NH (perched on ceiling of cave inside the waterfall)
- Fort Brennand, Roanoke Ridge, NH (perched in southwest crows nest)
- Pleasance, Scarlett Meadows, LE (inside the schoolhouse damaged by a fallen tree; south of 'c' in "Pleasan**c**e")
- Canebreak Manor, Bluewater Marsh, LE (flying over the marsh flats)
- Bayall Edge, Bayou Nwa, LE (perched on the front of the cabin)
- Braithewaite Manor, Scarlett Meadows, LE (flying around the boat house on the east shore of Flat Iron Lake)
- Bolger Glade, Scarlett Meadows, LE (flying overhead, usually towards Flat Iron Lake)
- Swadbass Point, Tall Trees, WE (perched on north side of cabin at **Aurora Basin**)

### Birds

*Small birds (sparrows, blue jays, woodpeckers, etc) are primarily diurnal, but can be stirred up while roosting at night.*

Most small birds can be found pretty much everywhere except **New Austin** (excluding **Hennigan's Stead, NA**). Hotspots for easy finds are along the entire **Dakota River** and **Kamassa River**. Look atop rocks in the water and near the shore.

## Extended Information

*Reference links to documents/maps that were used, among other things.*

### Testing Procedures

- PC v1436 locked at 60fps, V-Sync off, Triple Buffering on, mostly medium settings aside from low lighting qualities and ultra textures.
- All animals are tracked back to their original locations via **Eagle Eye**. All locations shown were verified at least twice before being marked.
- Dismount horse well away from spawn.
- Constant application of **Cover Scent Lotion**, as in once every 2-3 minutes.
- Slow approach, normal crouched walking.
- RampageTrainer (freeze/change time/weather; 2021/12/05 using Ignored By Wild Animals to pinpoint exact spawn locations)

### Release Format

The releases are 7z format with LZMA2 compression, so you'll need an archiving program capable of extracting LZMA2 7-zip archives. I use [7-zip itself](https://www.7-zip.org/), but you're free to use whatever you want.

In-game screenshots of the player sitting at a "sit" location are uploaded in their own, separate archives with the suffix `SitLocationsInGame` (i.e. `rdr2-maps-2021-11-07-SitLocationsInGame.7z`).

### Map References

[Original map, a fantastic 10MP hillshaded render](https://www.reddit.com/r/reddeadredemption/comments/gimo7v/10mp_rdr2_game_map_redux_enhanced_with_hillshaded/) by Reddit user [domriccobene](https://www.reddit.com/user/domriccobene/).

[RDOMap](https://jeanropke.github.io/RDOMap/) and its associated [contributors](https://github.com/jeanropke/RDOMap/blob/master/CONTRIBUTORS.md) for nearly all sit locations.

[Sit map](https://www.reddit.com/r/RedDeadOnline/comments/bzv17m/for_those_of_you_who_like_to_stay_classy_even/) by Reddit user [Impossible_Phase](https://www.reddit.com/user/Impossible_Phase/).

[ViktorFekete](https://gtaforums.com/profile/1197324-viktorfekete/) for narrowing the search area for cougars around **Benedict Point, Gaptooth Ridge, NA**.

[Looser3241](https://gtaforums.com/profile/1225578-looser3241/) for the sit location at **Clemens Point, Scarlett Meadows, LE**. [Cutter de Blanc](https://gtaforums.com/profile/642145-cutter-de-blanc/) for testing the location.

For select animal population maps:
- [Red Dead Wiki](https://reddead.fandom.com/)
- [GosuNoob](https://www.gosunoob.com/red-dead-redemption-2/)
- [GTABase](https://gtabase.com/)
- [RDR2.org](https://rdr2.org/)
- [PowerPyx's Guides](https://www.powerpyx.com/red-dead-redemption-2-all-animal-locations-zoologist-skin-deep/)

### Programs Used

- [GNU Image Manipulation Program](https://www.gimp.org/) - *Editing maps.*
- [RampageTrainer](https://www.nexusmods.com/reddeadredemption2/mods/233) - *To change/freeze time of day and/or weather*
- [ScriptHookRDR2](https://www.dev-c.com/rdr2/scripthookrdr2/) - *RampageTrainer dependency*
- [GreenShot](https://github.com/greenshot/greenshot) - Capturing in-game screenshots.
- [nomacs](https://github.com/nomacs/nomacs) - Scan through screenshots when marking new locations.
- [CheatEngine](https://www.cheatengine.org/download/CheatEngine7.2_MissingSetup.rar) - *portable version; used for speedhack to make time fly by.*
- [7-Zip](https://www.7-zip.org/) - *Archiving and compressing.*
- [VS Code](https://code.visualstudio.com/) - *Editing and previewing Markdown docs.*

### Quotes

[Abe (Ep. I, Simple Pleasures)](https://game-scripts.fandom.com/wiki/Red_Dead_Redemption_2#Simple_Pleasures)

> It’s changed. Rich fellers are coming in and buying everything... the ranches... but... well, it ain’t as wild as it once were, at least. 

[Charles Smith (Ep. II, Bare Knuckle Friendships)](https://game-scripts.fandom.com/wiki/Red_Dead_Redemption_2#Bare_Knuckle_Friendships)

> Those are Guido Martelli's men.
