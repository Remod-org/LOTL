# LOTL

## Living Off The Loot - Inspired by Faceless

See his OLD series starting with https://www.youtube.com/watch?v=X6_ldOgxCw0

This is intended to be run as the ONLY plugin for PVP.  It will prevent decay since resources are so rare to obtain.  If configured, a small number of players will randomly be issued bypass permissions allowing the abililty to obtain resources such as wood and stone.  Also, by default, admins can also gather resources.

 - The bypass permission will only last while they are connected.
 - The permission will only be granted to UP TO 10% of the current active players.

Otherwise:

 - NO farming: trees, nodes, barrels, animals
 - NO picking up: stone, metal, sulfur, wood
 - NO harvesting: wild veg, hemp
 - CAN LOOT: bodies, items on the ground, directly lootable objects, your own plants from seed
 - CAN CRAFT: all

```js
{
  "debug": false,
  "seedPlayers": true,
  "allowAdmin": true,
  "Version": {
    "Major": 1,
    "Minor": 0,
    "Patch": 1
  }
}
```

TODO:

  1. Allow the admin by command to disable the bypass altogether, e.g. for seeding players with resources only during the first few days, etc.

  2. Potentially remove the permission once a player is killed.  They could also have the chance to re-obtain it on spawn, but this could lead to abuse.

