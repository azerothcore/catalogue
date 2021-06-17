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
- Core hooks used:
    + PlayerScript: OnLogin, OnFirstLogin

# Description

This module teleports new characters on first login to a location defined in the configuration file (ideal for PvP servers).
You can also enable an option to clean the player's inventory on first login.
