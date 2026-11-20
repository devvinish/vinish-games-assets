# ARCHFIRE assets: credits and licences

ARCHFIRE is a first-person hostage-rescue shooter on vinish.dev. This folder holds the game's models, textures and sounds.
Every file was reduced for phones: meshes simplified and meshopt-compressed, textures resized and re-encoded as WebP.
All characters, places and weapon names in the game are invented. The kidnappers wear plain gear: printed unit names, badges and brand marks were painted out of every texture.

Sound credits are in [CREDITS-sounds.md](CREDITS-sounds.md) (all CC0).

## Guns: Sketchfab (CC BY 4.0)

| File | Source | Author | Licence | Changes |
|---|---|---|---|---|
| `models/af-carbine.glb` | [Custom Carbine Rifle NV4 COD](https://sketchfab.com/3d-models/custom-carbine-rifle-nv4-cod-195d2de670b24e22a98cf9d47607e646) | [trolosqlfod](https://sketchfab.com/trolosqlfod) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Printed brand text and logos painted out; simplified; textures resized; compressed |
| `models/af-pistol.glb` | [9mm Pistol](https://sketchfab.com/3d-models/9mm-pistol-43bc09f5aace4346a8a2b6e1580fc03f) | [TORI106](https://sketchfab.com/TORI106) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Printed text painted out; textures resized; compressed |
| `models/af-shotgun.glb` | [M4 Super 90 (JW2) Brand-Friendly version](https://sketchfab.com/3d-models/m4-super-90-jw2-brand-friendly-version-7e472e24152246708cac8b6f1613c7a8) | [8sianDude](https://sketchfab.com/haoliu95) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Printed text painted out; simplified; textures resized; compressed |
| `models/af-sniper.glb` | [Modern Sniper Rifle, Free Lowpoly](https://sketchfab.com/3d-models/modern-sniper-rifle-free-lowpoly-45c99509f1ee4c2a8c9c3336d3e2ff5a) | [Vlasov Daniil](https://sketchfab.com/dan741vlasov) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Printed text painted out; textures resized; compressed. Called "RIFLE" in the game |

## Characters and animations: Mixamo (Adobe)

The characters and motions come from [Mixamo](https://www.mixamo.com), converted from FBX to GLB and then reduced. All motions are retargeted in the game from one shared skeleton.
Mixamo content is royalty-free for personal, commercial and non-profit projects, games included, under the Adobe General Terms of Use and the Mixamo FAQ.

| File | Mixamo source | Changes |
|---|---|---|
| `models/af-gasmask.glb` | Character "Gas Mask" (kidnapper) | "SWAT" and "POLICE" prints and a shoulder badge painted out of the texture; simplified; compressed |
| `models/af-swat.glb` | Character "Swat Guy" (kidnapper, and the player's arms) | Simplified; compressed |
| `models/af-kate.glb` | Character "Kate" (hostage) | Simplified; compressed |
| `models/af-joe.glb` | Character "Joe" (hostage) | Simplified; compressed |
| `models/af-anims.glb`, clip `aim` | Motion "Rifle Aiming Idle" | |
| clip `fire` | Motion "Firing Rifle" | |
| clip `idle` | Motion "Rifle Idle" | |
| clip `walk` | Motion "Walk With Rifle" | |
| clip `run` | Motion "Rifle Run" | |
| clip `hit` | Motion "Hit Reaction" | |
| clip `death` | Motion "Rifle Death" | |
| clip `reload` | Motion "Reloading" | |
| clip `holder` | Motion "Hostage Situation Idle - Villain" | |
| clip `sit` | Motion "Sitting" | Frozen, arms tied back in the game |
| clip `held` | Motion "Hostage Situation Idle - Hostage" | |
| clip `standup` | Motion "Stand Up" | |
| clip `terrified` | Motion "Terrified" | |
| clip `hrun` | Motion "Running" | |
| clip `thankful` | Motion "Thankful" | |

## Props: Poly Haven (CC0)

All in `models/af-props.glb`, from [Poly Haven](https://polyhaven.com), released under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Credit is not required but given gladly. Changes: scaled, textures resized to WebP, meshes simplified and compressed.

[Painted Wooden Chair 02](https://polyhaven.com/a/painted_wooden_chair_02),
[Plastic Monobloc Chair 01](https://polyhaven.com/a/plastic_monobloc_chair_01),
[Wooden Crate 01](https://polyhaven.com/a/wooden_crate_01),
[Wooden Crate 02](https://polyhaven.com/a/wooden_crate_02),
[Wooden Military Crate](https://polyhaven.com/a/wooden_military_crate),
[Barrel 01](https://polyhaven.com/a/Barrel_01),
[Barrel 03](https://polyhaven.com/a/barrel_03),
[Metal Jerrycan](https://polyhaven.com/a/metal_jerrycan),
[Metal Jerrycan Green](https://polyhaven.com/a/metal_jerrycan_green),
[Ammo Box](https://polyhaven.com/a/ammo_box),
[Medical Box](https://polyhaven.com/a/medical_box),
[Lantern 01](https://polyhaven.com/a/Lantern_01),
[Wooden Table 01](https://polyhaven.com/a/WoodenTable_01),
[Vintage Radio Transceiver](https://polyhaven.com/a/vintage_radio_transceiver),
[Stone Fire Pit](https://polyhaven.com/a/stone_fire_pit),
[Namaqualand Boulder 02](https://polyhaven.com/a/namaqualand_boulder_02),
[Namaqualand Boulder 04](https://polyhaven.com/a/namaqualand_boulder_04),
[Folding Wooden Stool](https://polyhaven.com/a/folding_wooden_stool).

## Textures and skies: Poly Haven (CC0)

From [Poly Haven](https://polyhaven.com), [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). Changes: resized and re-encoded as WebP.

| File | Poly Haven asset |
|---|---|
| `textures/af-wall.webp`, `af-wall-n.webp` | [Old Sandstone 02](https://polyhaven.com/a/old_sandstone_02) |
| `textures/af-wall2.webp`, `af-wall2-n.webp` | [Defense Wall](https://polyhaven.com/a/defense_wall) |
| `textures/af-floor.webp`, `af-floor-n.webp` | [Large Sandstone Blocks 01](https://polyhaven.com/a/large_sandstone_blocks_01) |
| `textures/af-pillar.webp`, `af-pillar-n.webp` | [Large Sandstone Blocks](https://polyhaven.com/a/large_sandstone_blocks) |
| `textures/af-rubble.webp`, `af-rubble-n.webp` | [Castle Wall Varriation](https://polyhaven.com/a/castle_wall_varriation) |
| `textures/af-wood.webp`, `af-wood-n.webp` | [Medieval Wood](https://polyhaven.com/a/medieval_wood) |
| `textures/af-sand.webp` | [Gravelly Sand](https://polyhaven.com/a/gravelly_sand) |
| `textures/af-dirt.webp` | [Dirt](https://polyhaven.com/a/dirt) |
| `textures/af-sky-day.webp` | [Kloofendal 48d Partly Cloudy (Pure Sky)](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky) |
| `textures/af-sky-dusk.webp` | [Qwantani Dusk 2 (Pure Sky)](https://polyhaven.com/a/qwantani_dusk_2_puresky) |

## Made in code

Arches, walls, roof, rubble, ropes, flames, muzzle flashes, smoke, sparks, bullet marks and the map are drawn by the game itself.
