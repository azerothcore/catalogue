# Module info

- Name: mod-dynamic-xp
- Author: Milestorme
- Repository: https://github.com/milestorme/mod-dynamic-xp
- Download: https://github.com/milestorme/mod-dynamic-xp/archive/master.zip
- License: AGPL

# Module integration

- AzerothCore hash/commit compliance: 4b27100
- Includes configuration (.conf)?: Yes, copied by CMake
- Includes SQL patches?: No
- CMake hooks used:
    + AFTER_WORLDSERVER_CMAKE
- Core hooks used: 
    + PlayerScript: OnLogin
    + PlayerScrpt: OnGiveXP
    

# Description

Set xp per level range e.g in dynamicxp.conf.

# Features

Dynamic.XP.Rate.1-9 = 1.0
Dynamic.XP.Rate.10-19 = 2.0
Dynamic.XP.Rate.20-29 = 3.0
Dynamic.XP.Rate.30-39 = 4.0
Dynamic.XP.Rate.40-49 = 5.0
Dynamic.XP.Rate.50-59 = 6.0
Dynamic.XP.Rate.60-69 = 7.0
Dynamic.XP.Rate.70-79 = 8.0
