## Docker Minecraft Server ##

A self-hosted ${\color{red}Modded}$ Minecraft server for me and my friends to play on!

This server is hosted on a Docker Container and uses the [CurseForge](https://www.curseforge.com) API to download modpacks listed in your `docker-compose.yaml` file.

<img src="server-utils/Server-Stats.png" alt="Member List" width="500"> <img src="server-utils/Docker-Icon.png" alt="Docker Logo" width="300">
![Server Listing](server-utils/Server-Listing-Boots.png)

## Mods ##
[Raspberry-flavoured](https://www.curseforge.com/minecraft/modpacks/raspberry-flavoured)
 
## Commands ##
_Build Command_: `docker compose up -d`
 
_Status_: `docker compose ps`
 
_Check Logs_: `docker compose logs -f`

_Stop Container_: `docker compose down`

## Reference
[docker-minecraft-server](https://github.com/itzg/docker-minecraft-server?tab=readme-ov-file)
