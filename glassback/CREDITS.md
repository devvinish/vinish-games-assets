# GLASSBACK assets: credits and licences

GLASSBACK is an arcade padel game on vinish.dev. This folder holds the game's models, textures and sounds.
Every file was reduced for phones: meshes simplified, textures resized and re-encoded (WebP inside the GLBs, JPG for the rest), meshes meshopt-compressed.

## Players and animations: Mixamo (Adobe)

Characters and motions come from [Mixamo](https://www.mixamo.com) and were converted from FBX to GLB, then reduced.
Mixamo content is royalty-free for personal, commercial and non-profit projects, games included, under the Adobe General Terms of Use and the Mixamo FAQ.
It is not CC0 or CC-BY. Adobe allows it inside a game, not as a standalone asset pack, so these files are here only to be loaded by GLASSBACK.

| File | Mixamo source |
|---|---|
| `models/gb-bryce.glb` | Character "Bryce" |
| `models/gb-sophie.glb` | Character "Sophie" |
| `models/gb-remy.glb` | Character "Remy" |
| `models/gb-shannon.glb` | Character "Shannon" |
| `models/gb-anims.glb`, clip `ready` | Motion "Goalkeeper Idle Without Ball" |
| `models/gb-anims.glb`, clip `idle` | Motion "Breathing Idle" |
| `models/gb-anims.glb`, clip `run` | Motion "Running Fast" |
| `models/gb-anims.glb`, clip `back` | Motion "Backwards Running" |
| `models/gb-anims.glb`, clips `side_l`, `side_r` | Motions "Goalkeeper Left Sidestep", "Goalkeeper Right Sidestep" |
| `models/gb-anims.glb`, clips `strafe_l`, `strafe_r` | Motions "Running Strafe To The Left", "Running Strafe To The Right" |
| `models/gb-anims.glb`, clip `cheer` | Motion "High Enthusiasm Fist Pump" |
| `models/gb-anims.glb`, clip `sad` | Motion "Showing Frustration After A Loss" |

The strokes (forehand, backhand, volleys, smash, serve) are not clips: the game drives the arms by inverse kinematics along real stroke paths, so the hand holds the racket and each swing follows the shot.

## Venue props and reflections: Poly Haven (CC0)

All from [Poly Haven](https://polyhaven.com), released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Credit is not required but given gladly.

| File | Poly Haven asset | Author(s) |
|---|---|---|
| `models/gb-bench.glb` | [Painted Wooden Bench](https://polyhaven.com/a/painted_wooden_bench) | Kirill Sannikov |
| `models/gb-bistro.glb` | [Outdoor Table Chair Set 01](https://polyhaven.com/a/outdoor_table_chair_set_01) | James Ray Cock |
| `models/gb-plant.glb` | [Potted Plant 04](https://polyhaven.com/a/potted_plant_04) | James Ray Cock |
| `models/gb-buoy.glb` | [Lifebuoy](https://polyhaven.com/a/lifebuoy) | Hank Kaamura |
| `textures/env-beach.jpg` | HDRI [Illovo Beach Balcony](https://polyhaven.com/a/illovo_beach_balcony) | Greg Zaal |
| `textures/env-harbour.jpg` | HDRI [Bell Park Pier](https://polyhaven.com/a/bell_park_pier) | Greg Zaal |
| `textures/env-canyon.jpg` | HDRI [Goegap Road](https://polyhaven.com/a/goegap_road) | Greg Zaal, James Ray Cock |
| `textures/env-rooftop.jpg` | HDRI [Hansaplatz](https://polyhaven.com/a/hansaplatz) | Greg Zaal |
| `textures/env-glacier.jpg` | HDRI [Dikhololo Night](https://polyhaven.com/a/dikhololo_night) | Greg Zaal |
| `textures/env-stadium.jpg` | HDRI [Dresden Station Night](https://polyhaven.com/a/dresden_station_night) | Greg Zaal |

The HDRIs are tone-mapped down to 1024x512 JPGs and used only as reflections on the glass, mesh and steel.

## Turf

`textures/turf-n.jpg` (normal map) and `textures/turf-g.jpg` (grain) were generated for GLASSBACK by `glassback/tools/turftex.mjs`. They are original work, released under CC0.

## Sounds: Freesound (CC0)

`snd/gb-sounds.mp3` is one sound sprite, cut, trimmed and normalised from these [Freesound](https://freesound.org) recordings, all released under CC0 1.0 (public domain).

| Slots | Sound | Author | Link |
|---|---|---|---|
| h1-h4, racket pops | "padel 2 edit" | Luisa_Sanchez | https://freesound.org/s/816833/ |
| sm, smash | "Tennis smash" | gprosser | https://freesound.org/s/412863/ |
| b1-b4, ball bounces | "TennisBallBounce.wav" | drivr3joe | https://freesound.org/s/533410/ |
| g1-g2, glass and wall | "Squash impact of the ball" | 14FPanskaBubik_Lukas | https://freesound.org/s/418549/ |
| v1, volley block | "Tennis impact" | 14FPanskaBubik_Lukas | https://freesound.org/s/418540/ |

Rebuild the sprite with `python3 glassback/tools/sndsprite.py <folder of the downloaded previews>`.
