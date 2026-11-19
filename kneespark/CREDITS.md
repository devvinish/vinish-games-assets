# KNEESPARK assets: credits and licences

KNEESPARK is a motorcycle Grand Prix racing game on vinish.dev. This folder holds the game's models, textures and sounds.
Every file was reduced for phones: meshes simplified and meshopt-compressed, textures resized and re-encoded.
All teams, riders, sponsors and circuits in the game are invented. No real team, rider, sponsor or series logo is used.

## Race bike and helmet: Sketchfab (CC BY 4.0)

| File | Source | Author | Licence | Changes |
|---|---|---|---|---|
| `models/ks-bike.glb` | [SuperGP v1](https://sketchfab.com/3d-models/supergp-v1-7470a25431404034ab7521135eada178) | [SuperBiker](https://sketchfab.com/SuperBiker) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Original textures and markings removed; parts grouped into paint zones that the game colours per fictional team; body, wheels, forks and bars split so they can move; simplified (with a low-detail version) and compressed |
| `models/ks-helmet.glb` | [Motorcycle Helmet](https://sketchfab.com/3d-models/motorcycle-helmet-dc3894945d474407bbd7a95553acdd31) | [XQCAD](https://sketchfab.com/XQCAD) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Textures removed; parts grouped into paint zones (shell, visor, trim) that the game colours per rider; simplified (with a low-detail version) and compressed |

## Trees: Sketchfab (CC BY 4.0)

The trees are the same billboard sheet as GRIDBURN's, `textures/ks-trees.webp`, rendered from these models (changes: rendered to 2D impostors, resized, colour bled into the transparent edges).

| Source | Author | Licence |
|---|---|---|
| [Billboard Tree Pack](https://sketchfab.com/3d-models/billboard-tree-pack-5636201ec3a241efbb33a67670a67340) | [sixonetwo](https://sketchfab.com/evan4129) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Coniferous Forest Assets Pack](https://sketchfab.com/3d-models/coniferous-forest-assets-pack-240ce9cf0ad3474f809a59f9446e63cd) | [Dari](https://sketchfab.com/dariiiii) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Cypress tree](https://sketchfab.com/3d-models/cypress-tree-249d8cb553a8469e9d645713f8e96ed1) | [ElectroNick](https://sketchfab.com/ElectroNick) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Realistic Palm Tree Free](https://sketchfab.com/3d-models/realistic-palm-tree-free-39052ea764c945858449e699318efa53) | [Next Spring](https://sketchfab.com/NextSpring) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Realistic Palm Tree 4 Free](https://sketchfab.com/3d-models/realistic-palm-tree-4-free-917c18d6b2d04d33950dea6e20bc074f) | [Next Spring](https://sketchfab.com/NextSpring) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Spruce tree](https://sketchfab.com/3d-models/spruce-tree-7a5db417827244d98827459bce0cc944) | [Georgeous](https://sketchfab.com/intice184) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

## Rider and animations: Mixamo (Adobe)

The rider character and motions come from [Mixamo](https://www.mixamo.com) and were converted from FBX to GLB, then reduced (with a low-detail version). The game poses the rider on the bike itself and tints the leathers in each team's colour.
Mixamo content is royalty-free for personal, commercial and non-profit projects, games included, under the Adobe General Terms of Use and the Mixamo FAQ.
It is not CC0 or CC-BY. Adobe allows it inside a game, not as a standalone asset pack, so these files are here only to be loaded by KNEESPARK.

| File | Mixamo source |
|---|---|
| `models/ks-rider.glb` | Character "Racer" |
| `models/ks-rider.glb`, clip `idle` | Motion "Breathing Idle" |
| `models/ks-rider.glb`, clip `cheer` | Motion "Cheering" |
| `models/ks-rider.glb`, clip `clap` | Motion "Clapping" |
| `models/ks-rider.glb`, clip `wave` | Motion "Waving" |
| `models/ks-rider.glb`, clip `victory` | Motion "Victory Idle" |

## Textures and skies: Poly Haven (CC0)

All from [Poly Haven](https://polyhaven.com), released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Credit is not required but given gladly. Changes: resized and re-encoded as JPG.

| File | Poly Haven asset |
|---|---|
| `textures/ks-asphalt.jpg`, `ks-asphalt-n.jpg` | [Clean Asphalt](https://polyhaven.com/a/clean_asphalt) |
| `textures/ks-runoff.jpg` | [Asphalt 04](https://polyhaven.com/a/asphalt_04) |
| `textures/ks-gravel.jpg`, `ks-gravel-n.jpg` | [Gravel Floor 03](https://polyhaven.com/a/gravel_floor_03) |
| `textures/ks-grass.jpg`, `ks-grass-n.jpg` | [Sparse Grass](https://polyhaven.com/a/sparse_grass) |
| `textures/ks-meadow.jpg`, `ks-meadow-n.jpg` | [Grass Ground](https://polyhaven.com/a/grass_ground) |
| `textures/ks-leaves.jpg`, `ks-leaves-n.jpg` | [Dry Decay Leaves](https://polyhaven.com/a/dry_decay_leaves) |
| `textures/ks-sand.jpg`, `ks-sand-n.jpg` | [Red Sand](https://polyhaven.com/a/red_sand) |
| `textures/ks-rock.jpg`, `ks-rock-n.jpg` | [Rock Face 03](https://polyhaven.com/a/rock_face_03) |
| `textures/ks-cliff.jpg`, `ks-cliff-n.jpg` | [Cliff Side](https://polyhaven.com/a/cliff_side) |
| `textures/ks-snow.jpg`, `ks-snow-n.jpg` | [Snow 02](https://polyhaven.com/a/snow_02) |
| `textures/ks-concrete.jpg` | [Concrete Floor 01](https://polyhaven.com/a/concrete_floor_01) |
| `textures/ks-sky-alpine.jpg` | HDRI [Pizzo Pernice (Pure Sky)](https://polyhaven.com/a/pizzo_pernice_puresky), tone-mapped |
| `textures/ks-sky-canyon.jpg` | HDRI [Lonely Road Afternoon (Pure Sky)](https://polyhaven.com/a/lonely_road_afternoon_puresky), tone-mapped |
| `textures/ks-sky-autumn.jpg` | HDRI [Evening Road 01 (Pure Sky)](https://polyhaven.com/a/evening_road_01_puresky), tone-mapped |

## Sounds: Freesound (CC0)

See [CREDITS-sounds.md](CREDITS-sounds.md): every sound is a Freesound upload released under CC0 1.0 (public domain), cut, looped and level-matched for the game.
