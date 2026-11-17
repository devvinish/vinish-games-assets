# GRIDBURN assets: credits and licences

GRIDBURN is an open-wheel Grand Prix racing game on vinish.dev. This folder holds the game's models, textures and sounds.
Every file was reduced for phones: meshes simplified and meshopt-compressed, textures resized and re-encoded.
All teams, drivers, sponsors and circuits in the game are invented. No real team, driver, sponsor or series logo is used.

## Race car: Sketchfab (CC BY 4.0)

| File | Source | Author | Licence | Changes |
|---|---|---|---|---|
| `models/gr-car.glb` | [F1 2022 {FREE!!}](https://sketchfab.com/3d-models/f1-2022-free-013c9e89d2244e37924031dfe4ccf4c3) | [3dblender_1](https://sketchfab.com/3dblender_1) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Original textures and markings removed; parts grouped into paint zones that the game colours per fictional team; body and wheels split, simplified (with a low-detail version) and compressed |

## Trees: Sketchfab (CC BY 4.0)

The trees were rendered from these models into one billboard sheet, `textures/gr-trees.webp` (changes: rendered to 2D impostors, resized, colour bled into the transparent edges).

| Source | Author | Licence |
|---|---|---|
| [Billboard Tree Pack](https://sketchfab.com/3d-models/billboard-tree-pack-5636201ec3a241efbb33a67670a67340) | [sixonetwo](https://sketchfab.com/evan4129) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Coniferous Forest Assets Pack](https://sketchfab.com/3d-models/coniferous-forest-assets-pack-240ce9cf0ad3474f809a59f9446e63cd) | [Dari](https://sketchfab.com/dariiiii) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Cypress tree](https://sketchfab.com/3d-models/cypress-tree-249d8cb553a8469e9d645713f8e96ed1) | [ElectroNick](https://sketchfab.com/ElectroNick) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Realistic Palm Tree Free](https://sketchfab.com/3d-models/realistic-palm-tree-free-39052ea764c945858449e699318efa53) | [Next Spring](https://sketchfab.com/NextSpring) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Realistic Palm Tree 4 Free](https://sketchfab.com/3d-models/realistic-palm-tree-4-free-917c18d6b2d04d33950dea6e20bc074f) | [Next Spring](https://sketchfab.com/NextSpring) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Spruce tree](https://sketchfab.com/3d-models/spruce-tree-7a5db417827244d98827459bce0cc944) | [Georgeous](https://sketchfab.com/intice184) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## Pit crew and animations: Mixamo (Adobe)

The crew character and motions come from [Mixamo](https://www.mixamo.com) and were converted from FBX to GLB, then reduced. The game tints the suits in each team's colour.
Mixamo content is royalty-free for personal, commercial and non-profit projects, games included, under the Adobe General Terms of Use and the Mixamo FAQ.
It is not CC0 or CC-BY. Adobe allows it inside a game, not as a standalone asset pack, so these files are here only to be loaded by GRIDBURN.

| File | Mixamo source |
|---|---|
| `models/gr-crew.glb` | Character "Racer" |
| `models/gr-anims.glb`, clip `idle` | Motion "Breathing Idle" |
| `models/gr-anims.glb`, clip `kneel` | Motion "Kneeling Idle" |
| `models/gr-anims.glb`, clip `kneel_work` | Motion "Kneeling Inspecting" |
| `models/gr-anims.glb`, clip `box` | Motion "Box Idle" |
| `models/gr-anims.glb`, clip `box_jog` | Motion "Jogging With Box" |
| `models/gr-anims.glb`, clip `carry` | Motion "Carrying" |
| `models/gr-anims.glb`, clip `push` | Motion "Pushing" |
| `models/gr-anims.glb`, clip `cheer` | Motion "Cheering" |
| `models/gr-anims.glb`, clip `clap` | Motion "Clapping" |
| `models/gr-anims.glb`, clip `wave` | Motion "Waving" |
| `models/gr-anims.glb`, clip `victory` | Motion "Victory Idle" |

## Textures and skies: Poly Haven (CC0)

All from [Poly Haven](https://polyhaven.com), released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Credit is not required but given gladly. Changes: resized and re-encoded as JPG.

| File | Poly Haven asset |
|---|---|
| `textures/gr-asphalt.jpg`, `gr-asphalt-n.jpg` | [Asphalt Track](https://polyhaven.com/a/asphalt_track) |
| `textures/gr-runoff.jpg`, `gr-runoff-n.jpg` | [Asphalt Pit Lane](https://polyhaven.com/a/asphalt_pit_lane) |
| `textures/gr-grass.jpg`, `gr-grass-n.jpg` | [Leafy Grass](https://polyhaven.com/a/leafy_grass) |
| `textures/gr-gravel.jpg`, `gr-gravel-n.jpg` | [Gravel Floor 02](https://polyhaven.com/a/gravel_floor_02) |
| `textures/gr-concrete.jpg`, `gr-concrete-n.jpg` | [Concrete Floor 02](https://polyhaven.com/a/concrete_floor_02) |
| `textures/gr-sand.jpg`, `gr-sand-n.jpg` | [Gravelly Sand](https://polyhaven.com/a/gravelly_sand) |
| `textures/gr-beach.jpg` | [Coast Sand 01](https://polyhaven.com/a/coast_sand_01) |
| `textures/gr-sky-coast.jpg` | HDRI [Kloofendal 48d Partly Cloudy (Pure Sky)](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky), tone-mapped |
| `textures/gr-sky-forest.jpg` | HDRI [Rustig Koppie (Pure Sky)](https://polyhaven.com/a/rustig_koppie_puresky), tone-mapped |
| `textures/gr-sky-dusk.jpg` | HDRI [Qwantani Dusk 2 (Pure Sky)](https://polyhaven.com/a/qwantani_dusk_2_puresky), tone-mapped |

## Sounds: Freesound (CC0)

All sounds are Freesound uploads released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain), cut, looped and level-matched for the game.
Slots `wg1` to `grav` are cut into the sprite `snd/gr-sfx.mp3`; `eng-lo` and `eng-hi` are the engine loops `snd/gr-eng-lo.mp3` and `snd/gr-eng-hi.mp3`; `crowd` is `snd/gr-crowd.mp3`.

| Slot | Sound | Author | Link | License |
|---|---|---|---|---|
| wg1, wg2 | Air Impact Wrench | sevenbsb | https://freesound.org/s/349398/ | CC0 |
| jack | release_air_pffft.wav | reg7783 | https://freesound.org/s/131302/ | CC0 |
| cr1 | Car Crash | squareal | https://freesound.org/s/237375/ | CC0 |
| cr2 | Clank Car Crash Collision | qubodup | https://freesound.org/s/151624/ | CC0 |
| cheer | RoaringCrowd.wav | benfree | https://freesound.org/s/130568/ | CC0 |
| skid | car park skiding corner.wav | martian | https://freesound.org/s/178889/ | CC0 |
| grav | car tire on gravel rear cu blyth 21 6 12.flac | TRP | https://freesound.org/s/577504/ | CC0 |
| eng-lo, eng-hi | motorbike hornet 600 onboard.clip 0005.N3.F.wav | martian | https://freesound.org/s/181161/ | CC0 |
| crowd | R08-54-Large Crowd Cheering at Event.wav | craigsmith | https://freesound.org/s/480765/ | CC0 |
