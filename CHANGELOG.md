### IMPORTANT ###
When a new release comes out be sure to watch out for config changes. All default values have been tested against a big userbase and 
changing those values will cause bypasses to happen (especially raising min_vl values). 

Config URL: THIS IS A SECRET TILL RELEASE.config

### General AAC 3 changes ###

1. Merged all MC Versions into one single AAC Version
2. Updated ProtocolLib to 4.1.0+

### Release AAC 3.0.0 ###
- Fixed AAC Teleport bypass
- Fixed AAC Fly bypass
- Fixed various bhop speeds
- Implemented many new killaura heuristics
- Combined angle and reach to new hitbox check
- Implemented cancel_vl_interact into interact check 
- Implemented cancel_vl_place into interact check
- Implemented cancel_vl_break into interact check
- Implemented phase exception list for known MC bugs (anvil, chest and enderchest)
- Completly rewrote impossible interact to account various fuckers and be able to configure different cancel vls
- Removed annoying forcefield entity as it got useless due to many cheat-clients ignoring it.
