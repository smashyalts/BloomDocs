**Palworld Useful Info**

## Known Issues / FAQ

1. The server won't show up in the Community-Server tab.
   -> This is a known problem and the devs will hopefully fix that asap. Best choice is to connect by IP and Password.
2. The server has a memory leak.
   -> This is also an issue that they are aware of.
   -> The `bEnableInvaderEnemy` option seems to have a huge impact on the current RAM usage. Disabling it might be choice.
   -> Tip: Schedule a server restart every 6h. You might adjust the value according to your system!
3. The server does not show up in the steam server list.
   -> This is currently and might never be supported.
4. The config file gets deleted / reset on server restart.
   -> Before editing the config file always make sure to fully stop the server first. Otherwise all changes wont be saved.

## Recommended server settings

### RAM

Due to at least one memory leak the server requires about 16-32GB RAM.
Referring to the [official documentation](https://tech.palworldgame.com/dedicated-server-guide) you can start the server with 8GB but you will run out of memory very quickly.
The minimum should be 16GB but 32GB are fairly recommended for now.

### CPU

Intel / AMD processor with at least 4 cores.

### Storage

As of January 19th 2024 the server requires about 5GB of storage capacity. This might extend with further content/updates.



**[Credit to original post](https://github.com/parkervcp/eggs/tree/master/game_eggs/steamcmd_servers/palworld)**

