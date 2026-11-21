# SPOKEFALL assets: credits and licences

SPOKEFALL is a downhill mountain bike racing game on vinish.dev. This folder holds the game's models, textures and sounds.
Every file was reduced for phones: meshes simplified and meshopt-compressed, textures resized and re-encoded.
All riders, trails and names in the game are invented. No real brand, team or rider is shown.

## Bike and helmet: Sketchfab (CC BY 4.0)

| File | Source | Author | Licence | Changes |
|---|---|---|---|---|
| `models/sf-bike.glb` | [Enduro bicycle DH](https://sketchfab.com/3d-models/enduro-bicycle-dh-79dfd2109aee44c8a0ec27dfb1d41c04) | Res1n | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Frame paint recoloured per rider; frame, fork, wheels, crank and pedals split so they can steer and spin; simplified (with a low-detail version) and compressed |
| `models/sf-helmet.glb` | [Full Face MTB Helmet](https://sketchfab.com/3d-models/full-face-mtb-helmet-2b0bb690bbca4453b6d385e4ee0f3294) | chett33 | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Textures removed; parts grouped into a shell and a peak that the game colours per rider; simplified (with a low-detail version) and compressed |

## Rider and animations: Mixamo (Adobe)

`models/sf-rider.glb` is the same file as KNEESPARK's `ks-rider.glb`: the Mixamo character "Racer" with the motions "Breathing Idle" (`idle`), "Cheering" (`cheer`), "Clapping" (`clap`), "Waving" (`wave`) and "Victory Idle" (`victory`), converted from FBX to GLB and reduced (with a low-detail version).
The game poses the rider on the bike itself and tints the kit in each rider's colours; the clips play on the spectators and the podium.
Mixamo content is royalty-free for personal, commercial and non-profit projects, games included, under the Adobe General Terms of Use and the Mixamo FAQ.
It is not CC0 or CC BY. Adobe allows it inside a game, not as a standalone asset pack, so this file is here only to be loaded by the game.

## Trees and rocks: the vinish.dev free 3D model library (CC BY 4.0)

`models/sf-nature.glb` packs models made by vinish.dev for its [free 3D model library](https://vinish.dev/free-3d-models) (CC BY 4.0): Pine Tree, Snowy Spruce, Birch Tree, Dead Tree, Fern, Grass Tuft, Saguaro Cactus, Tree Stump, Granite Boulder, Boulder Set, Rock Pile and Snowy Rocks.
Changes: merged into one file, simplified (rocks with a low-detail version) and compressed.

## Textures and skies: Poly Haven (CC0)

All from [Poly Haven](https://polyhaven.com), released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Credit is not required but given gladly. Changes: resized and re-encoded as JPG.
Some files are KNEESPARK's resized copies of the same Poly Haven assets.

| File | Poly Haven asset |
|---|---|
| `textures/sf-dirt.jpg`, `sf-dirt-n.jpg` | [Dirt Floor](https://polyhaven.com/a/dirt_floor) |
| `textures/sf-mud.jpg`, `sf-mud-n.jpg` | [Brown Mud 02](https://polyhaven.com/a/brown_mud_02) |
| `textures/sf-rocky.jpg`, `sf-rocky-n.jpg` | [Brown Mud Rocks 01](https://polyhaven.com/a/brown_mud_rocks_01) |
| `textures/sf-forest.jpg`, `sf-forest-n.jpg` | [Forest Leaves 04](https://polyhaven.com/a/forest_leaves_04) |
| `textures/sf-planks.jpg`, `sf-planks-n.jpg` | [Brown Planks 07](https://polyhaven.com/a/brown_planks_07) |
| `textures/sf-grass.jpg`, `sf-grass-n.jpg` | [Sparse Grass](https://polyhaven.com/a/sparse_grass) |
| `textures/sf-meadow.jpg`, `sf-meadow-n.jpg` | [Grass Ground](https://polyhaven.com/a/grass_ground) |
| `textures/sf-sand.jpg`, `sf-sand-n.jpg` | [Red Sand](https://polyhaven.com/a/red_sand) |
| `textures/sf-rock.jpg`, `sf-rock-n.jpg` | [Rock Face 03](https://polyhaven.com/a/rock_face_03) |
| `textures/sf-cliff.jpg`, `sf-cliff-n.jpg` | [Cliff Side](https://polyhaven.com/a/cliff_side) |
| `textures/sf-snow.jpg`, `sf-snow-n.jpg` | [Snow 02](https://polyhaven.com/a/snow_02) |
| `textures/sf-sky-meadow.jpg` | HDRI [Kloofendal 48d Partly Cloudy (Pure Sky)](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky), tone-mapped |
| `textures/sf-sky-overcast.jpg` | HDRI [Kloofendal Overcast (Pure Sky)](https://polyhaven.com/a/kloofendal_overcast_puresky), tone-mapped |
| `textures/sf-sky-golden.jpg` | HDRI [Qwantani Late Afternoon (Pure Sky)](https://polyhaven.com/a/qwantani_late_afternoon_puresky), tone-mapped |
| `textures/sf-sky-snow.jpg` | HDRI [Snow Field (Pure Sky)](https://polyhaven.com/a/snow_field_puresky), tone-mapped |
| `textures/sf-sky-alpine.jpg` | HDRI [Pizzo Pernice (Pure Sky)](https://polyhaven.com/a/pizzo_pernice_puresky), tone-mapped |
| `textures/sf-sky-canyon.jpg` | HDRI [Lonely Road Afternoon (Pure Sky)](https://polyhaven.com/a/lonely_road_afternoon_puresky), tone-mapped |

## Sounds and music: Freesound (CC0)

Every sound and both music tracks are CC0 uploads on Freesound; the full list, with authors and links, is in [CREDITS-sounds.md](CREDITS-sounds.md).
