# Module info

- Name: Anti Farming System
- Author: Erictemponi
- Repository: https://github.com/erictemponi/mod-antifarming
- Download: https://github.com/erictemponi/mod-antifarming/archive/master.zip
- License: AGPL

# Module integration

- AzerothCore hash/commit compliance: [4313037](https://github.com/azerothcore/azerothcore-wotlk/commit/431303729855c7947ec52817c938035231436386)
- Includes configuration (.conf)?: Yes, copied by CMake
- Includes SQL patches?: No
- CMake hooks used:
    + AFTER_WORLDSERVER_CMAKE
- Core hooks used: 
    + PlayerScript: OnLogin, OnPVPKill
    + WorldScript: OnBeforeConfigLoad, OnAfterConfigLoad
    + CommandScript: GetCommands

# Description

A system that prevents players from farming (killing other players with same ip address or low health)
