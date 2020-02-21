# Module Info

- Name: TeleNewPlayers
- Author: Skxawng-cu
- Module TeleNewPlayers:
  + Repository: https://github.com/skxawng-cu/mod-tele-new-players
  + Download: https://github.com/skxawng-cu/mod-tele-new-players/archive/master.zip
- License: AGPL

# Module integration

- AzerothCore hash/commit compliance: 90ed254
- Includes configuration (.conf)?: Yes, copied by CMake
- Includes SQL patches?: No
- CMake hooks used:
    + AFTER_WORLDSERVER_CMAKE
- Core hooks used:
    + PlayerScript: OnLogin, OnFirstLogin

# Description

This module allows you to config coords for alliance and horde to teleport the new players after the first login (Ideal for PvP servers).
You cal also enable option to clean the player inventory on first login.
