# Autospawn Topology Guide

This document serves as a guide to all auto-spawned entities using topology to determine spawn locations.

For entities to autospawn you need a sizebale area with the appropriate splat, biome and topologies. Creating little blobs of the conditions will likely result in
them not spawning there.

**Splat** - The entity will only spawn in areas where any of these splat types are located

**Biome** - The entity will only spawn in areas where any of these biome types are located
  
**Required Topology** - The entity will only spawn in areas where all of these topology types are located
  
**Blocked Topology** - The entity will not spawn in areas where any of these topology types are located
  
**Any Topology** - The entity will only spawn in areas where any of these topology types are located


| Entity | Splat | Biome | Required Topology | Blocked Topology | Any Topology |
| --- | --- | --- | --- | --- | --- |
| | 2module_car_spawned.entity | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Road and Roadside |
| 3module_car_spawned.entity | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Road and Roadside |
| 4module_car_spawned.entity | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Road and Roadside |
| american_beech_a | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| american_beech_a | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| american_beech_a_dead | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| american_beech_b | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| american_beech_b | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| american_beech_c | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| american_beech_c | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| american_beech_d | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| american_beech_d | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| american_beech_e | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| american_beech_e | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| american_beech_e_dead | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| bear | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate, Tundra and Arctic | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| berry-blue-collectable | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| berry-green-collectable | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| berry-red-collectable | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| berry-white-collectable | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| berry-yellow-collectable | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| birch_big_temp | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| birch_big_temp | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| birch_big_tundra | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| birch_big_tundra | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| birch_large_temp | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| birch_large_temp | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| birch_large_tundra | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| birch_large_tundra | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| birch_medium_temp | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| birch_medium_temp | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Alt |
| birch_medium_tundra | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| birch_medium_tundra | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| birch_small_temp | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| birch_small_temp | Grass | Temperate | None | Field, Cliff, Summit, Ocean, Road, Swamp, River, Lake, Offshore, Building and Cliffside | Beachside, Riverside and Lakeside |
| birch_small_temp | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| birch_small_tundra | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| birch_small_tundra | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| birch_tiny_temp | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| birch_tiny_temp | Grass | Temperate | None | Field, Cliff, Summit, Ocean, Road, Swamp, River, Lake, Offshore, Building and Cliffside | Beachside, Riverside and Lakeside |
| birch_tiny_temp | Grass and Forest | Temperate | Alt | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline and Building | Forestside and Alt |
| birch_tiny_tundra | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| birch_tiny_tundra | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| boar | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid and Temperate | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| bush_spicebush_a | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_a | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_spicebush_a | Grass | Tundra | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_a | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_spicebush_a | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_spicebush_a_snow | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_spicebush_a_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_spicebush_b | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_b | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_spicebush_b | Grass | Tundra | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_b | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_spicebush_b | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_spicebush_c | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_c | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_spicebush_c | Grass | Tundra | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_c | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_spicebush_c | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_spicebush_c_snow | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_spicebush_c_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_spicebush_d | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_d | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_spicebush_d | Grass | Tundra | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_spicebush_d | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_spicebush_d | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_willow_a | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_willow_a | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_willow_a | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_willow_a | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_willow_b | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_willow_b | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_willow_b | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_willow_b | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_willow_c | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_willow_c | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_willow_c | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_willow_c | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_willow_d | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| bush_willow_d | Grass | Temperate | None | Cliff, Ocean, Decor, Monument, Road, River, Lake, Building and Alt | Beachside, Beach, Riverside and Lakeside |
| bush_willow_d | Grass and Forest | Temperate | None | Cliff, Beach, Ocean, Decor, Monument, Road, River, Lake, Plain, Building and Cliffside | Forest and Alt |
| bush_willow_d | Grass and Forest | Temperate | None | Cliff, Ocean, Oceanside, Decor, Road, River, Lake, Plain and Building | Forestside |
| bush_willow_snow_a | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_willow_snow_a | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| bush_willow_snow_a | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_willow_snow_b | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_willow_snow_b | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| bush_willow_snow_b | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_willow_snow_c | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_willow_snow_c | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| bush_willow_snow_c | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_willow_snow_d | Sand, Grass and Forest | Arctic | None | Cliff, Beach, Forest, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Forestside |
| bush_willow_snow_d | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| bush_willow_snow_d | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Clutter | Forest |
| bush_willow_snow_small_a | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| bush_willow_snow_small_b | Snow | Arctic | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Building and Alt | Field |
| cactus-1 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-2 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-3 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-4 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-5 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-6 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| cactus-7 | Dirt and Sand | Arid | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field |
| chicken | Dirt, Sand, Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| corn-collectable | Grass and Forest | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Riverside and Lakeside |
| creosote_bush_a | Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| creosote_bush_b | Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| creosote_bush_c | Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| creosote_bush_c | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| creosote_bush_d | Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| creosote_bush_d | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| creosote_bush_dry_a | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| creosote_bush_dry_b | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| dead_log_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Tundra | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_a | Snow | Arctic | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Tundra | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_b | Snow | Arctic | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Tundra | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| dead_log_c | Snow | Arctic | None | Cliff, Summit, Ocean, Decor, Road, Roadside, Swamp, River, Lake, Offshore, Plain and Building | Forest and Forestside |
| divesite_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Ocean, Oceanside and Offshore |
| divesite_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Ocean, Oceanside and Offshore |
| divesite_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Ocean, Oceanside and Offshore |
| douglas_fir_a | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| douglas_fir_a | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| douglas_fir_a_snow | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| douglas_fir_b | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| douglas_fir_b | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| douglas_fir_b_snow | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| douglas_fir_c | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| douglas_fir_c | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| douglas_fir_c_snow | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| douglas_fir_d | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| douglas_fir_d | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forestside |
| douglas_fir_d_small | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| driftwood_1 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Monument, Road, Swamp, River, Lake, Plain, Building and Cliffside | Beach |
| driftwood_2 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Monument, Road, Swamp, River, Lake, Plain, Building and Cliffside | Beach |
| driftwood_3 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Monument, Road, Swamp, River, Lake, Plain, Building and Cliffside | Beach |
| driftwood_4 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Monument, Road, Swamp, River, Lake, Plain, Building and Cliffside | Beach |
| driftwood_5 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Monument, Road, Swamp, River, Lake, Plain, Building and Cliffside | Beach |
| hemp-collectable | Dirt, Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Beach, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field and Forest |
| horse | Grass | Arid and Temperate | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| hotairballoon | Dirt, Snow, Sand, Grass, Forest, Stones and Gravel | Arid, Temperate and Arctic | None | Cliff, Beachside, Beach, Forest, Ocean, Oceanside, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside and Mountain | Field, Roadside and Plain |
| junkpile_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_d | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_e | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_f | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_g | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Roadside and Powerline |
| junkpile_water_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Offshore |
| junkpile_water_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Offshore |
| junkpile_water_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | None | Offshore |
| loot-barrel-1 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Monument |
| loot-barrel-2 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Monument |
| metal-collectable | Dirt, Snow, Sand, Grass and Forest | Arid, Temperate and Tundra | None | Cliff, Summit, Beach, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field and Forest |
| metal-ore | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| metal-ore | Sand | Arid | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| metal-ore | Snow | Arctic | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| minicopter.entity | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Road |
| mormon_tea_a | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| mormon_tea_b | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| mormon_tea_c | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| mormon_tea_d | Sand | Arid | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| murderer | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Monument, Roadside and Powerline |
| mushroom-cluster-5 | Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| mushroom-cluster-6 | Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| oak_b | Grass | Temperate | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, Swamp, River, Lake, Offshore, Powerline, Plain, Building, Clutter and Alt | Field, Decor, Cliffside and Hilltop |
| oak_c | Grass | Temperate | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, Swamp, River, Lake, Offshore, Powerline, Plain, Building, Clutter and Alt | Field, Decor, Cliffside and Hilltop |
| oak_d | Grass | Temperate | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, Swamp, River, Lake, Offshore, Powerline, Plain, Building, Clutter and Alt | Field, Decor, Cliffside and Hilltop |
| oak_e | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| oak_f | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| ocotillo_a | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_b | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_c | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_d | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_dry_a | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_dry_b | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_dry_c | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| ocotillo_dry_d | Sand, Grass and Forest | Arid | None | Cliff, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field, Forest, Forestside and Cliffside |
| palm_tree_med_a_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_med_a_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| palm_tree_short_a_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_short_a_entity | Grass | Arid | None | Cliff, Summit, Beach, Forest, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field, Cliff, Beachside, Forestside, Riverside and Lakeside |
| palm_tree_short_a_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_short_a_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| palm_tree_short_b_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_short_b_entity | Grass | Arid | None | Cliff, Summit, Beach, Forest, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field, Cliff, Beachside, Forestside, Riverside and Lakeside |
| palm_tree_short_b_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_short_b_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| palm_tree_short_c_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_short_c_entity | Grass | Arid | None | Cliff, Summit, Beach, Forest, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field, Cliff, Beachside, Forestside, Riverside and Lakeside |
| palm_tree_short_c_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_short_c_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| palm_tree_small_a_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_small_b_entity | Grass | Arid | None | Cliff, Summit, Beach, Forest, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field, Cliff, Beachside, Forestside, Riverside and Lakeside |
| palm_tree_small_b_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_small_c_entity | Grass | Arid | None | Cliff, Summit, Beach, Forest, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Field, Cliff, Beachside, Forestside, Riverside and Lakeside |
| palm_tree_small_c_entity | Sand | Arid | None | Field, Cliff, Summit, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Riverside and Lakeside |
| palm_tree_tall_a_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_tall_a_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| palm_tree_tall_b_entity | Forest | Arid | None | Summit, Ocean, Road, Swamp, River, Lake, Offshore, Plain and Building | Beachside, Forest, Lakeside and Cliffside |
| palm_tree_tall_b_entity | Sand and Grass | Arid | None | Field, Cliff, Summit, Beach, Forest, Forestside, Ocean, Decor, Road, Swamp, Lake, Offshore, Plain and Building | Beachside, River, Riverside, Lake and Lakeside |
| pine_a | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_a | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_a | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| pine_a_snow | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_a_snow | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_b | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| pine_b | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_b | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forestside |
| pine_b | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| pine_b snow | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_c | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_c | Grass and Forest | Temperate | Forest | Cliff, Summit, Beachside, Beach, Forestside, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forest |
| pine_c_snow | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_d | Grass | Temperate | None | Cliff, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Building, Clutter and Alt | Field and Cliffside |
| pine_d | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_d | Grass and Forest | Temperate | None | Cliff, Summit, Beachside, Beach, Forest, Ocean, Road, Swamp, River, Lake, Offshore, Powerline, Building and Alt | Forestside |
| pine_d | Grass and Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forestside |
| pine_d_snow | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_dead_a | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_b | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_c | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_d | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_d | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| pine_dead_e | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_e | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| pine_dead_f | Forest | Tundra | None | Cliff, Beachside, Beach, Ocean, Road, Swamp, River, Lake, Offshore and Building | Forest |
| pine_dead_f | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field and Cliffside |
| pine_dead_snow_a | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_b | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_c | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_d | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_e | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_e | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_dead_snow_f | Snow | Arctic | None | Field, Cliff, Summit, Beachside, Beach, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline, Plain and Building | Forest |
| pine_dead_snow_f | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_sapling_a | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_sapling_a | Grass and Forest | Tundra | None | Cliff, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Powerline and Building | Forest and Forestside |
| pine_sapling_a_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Ocean, Oceanside, Monument, Road, River, Lake, Powerline, Plain, Building and Cliffside | Forest and Forestside |
| pine_sapling_b | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_sapling_b | Grass and Forest | Tundra | None | Cliff, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Powerline and Building | Forest and Forestside |
| pine_sapling_b_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Ocean, Oceanside, Monument, Road, River, Lake, Powerline, Plain, Building and Cliffside | Forest and Forestside |
| pine_sapling_c | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_sapling_c | Grass and Forest | Tundra | None | Cliff, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Powerline and Building | Forest and Forestside |
| pine_sapling_c_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Ocean, Oceanside, Monument, Road, River, Lake, Powerline, Plain, Building and Cliffside | Forest and Forestside |
| pine_sapling_d | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_sapling_d | Grass and Forest | Tundra | None | Cliff, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Powerline and Building | Forest and Forestside |
| pine_sapling_d_snow | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_sapling_d_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Ocean, Oceanside, Monument, Road, River, Lake, Powerline, Plain, Building and Cliffside | Forest and Forestside |
| pine_sapling_e | Grass | Tundra | None | Cliff, Beachside, Beach, Forest, Forestside, Ocean, Road, Swamp, River, Lake, Offshore and Building | Field |
| pine_sapling_e | Grass and Forest | Tundra | None | Cliff, Beach, Ocean, Oceanside, Decor, Monument, Road, River, Lake, Powerline and Building | Forest and Forestside |
| pine_sapling_e_snow | Snow and Grass | Arctic | None | Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Road, River, Lake, Offshore, Powerline and Building | Field |
| pine_sapling_e_snow | Snow, Grass and Forest | Arctic | None | Cliff, Beach, Ocean, Oceanside, Monument, Road, River, Lake, Powerline, Plain, Building and Cliffside | Forest and Forestside |
| potato-collectable | Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Forest |
| pumpkin-collectable | Grass and Forest | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Riverside and Lakeside |
| rhib | Dirt, Sand, Grass, Forest, Stones and Gravel | Arid and Tundra | Ocean | Beachside and Beach | Ocean |
| rowboat | Dirt, Sand, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | Beach | Beachside | Oceanside, River, Riverside, Lake and Lakeside |
| scarecrow | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Monument, Roadside and Powerline |
| scraptransporthelicopter | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Field and Road |
| stag | Grass and Forest | Temperate and Tundra | None | Cliff, Summit, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| stone-collectable | Dirt, Snow, Sand, Grass and Forest | Arid, Temperate and Tundra | None | Cliff, Summit, Beach, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field and Forest |
| stone-ore | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| stone-ore | Sand | Arid | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| stone-ore | Snow | Arctic | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| sulfur-collectable | Dirt, Snow, Sand, Grass and Forest | Arid, Temperate and Tundra | None | Cliff, Summit, Beach, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field and Forest |
| sulfur-ore | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| sulfur-ore | Sand | Arid | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| sulfur-ore | Snow | Arctic | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Plain and Building | Decor, Cliffside and Clutter |
| swamp_tree_a | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| swamp_tree_b | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| swamp_tree_c | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| swamp_tree_d | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| swamp_tree_e | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| swamp_tree_f | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Ocean, Oceanside, Road, Roadside, Offshore, Powerline, Mountain and Hilltop | Swamp |
| testridablehorse | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid and Temperate | None | Cliff, Summit, Forest, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Powerline, Building, Cliffside, Mountain, Clutter and Hilltop | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| trash-pile-1 | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, River, Lake, Offshore, Building, Cliffside, Mountain and Clutter | Monument |
| wolf | Dirt, Snow, Sand, Grass, Forest, Stones and Gravel | Arid, Temperate and Tundra | None | Cliff, Summit, Beachside, Beach, Ocean, Oceanside, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
| wood-collectable | Grass and Forest | Arid, Temperate and Tundra | None | Summit, Beach, Ocean, Decor, Road, Swamp, River, Lake, Offshore, Powerline, Plain, Building, Mountain and Clutter | Field, Cliff, Beachside, Forest, Forestside, Oceanside, Riverside, Lakeside and Cliffside |
| zombie | Dirt, Snow, Sand, Rock, Grass, Forest, Stones and Gravel | Arid, Temperate, Tundra and Arctic | None | Cliff, Summit, Ocean, Decor, Monument, Road, Swamp, River, Lake, Offshore, Plain, Building, Cliffside, Mountain and Clutter | Field, Cliff, Summit, Beachside, Beach, Forest, Forestside, Ocean, Oceanside, Decor, Monument, Road, Roadside, Swamp, River, Riverside, Lake, Lakeside, Offshore, Powerline, Plain, Building, Cliffside, Mountain, Clutter, Alt, Tier0, Tier1, Tier2, Mainland and Hilltop |
