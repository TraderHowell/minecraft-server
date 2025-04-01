# minecraftd
✨ **Simple Minecraft server management.**  
🐉 [WIP] Here be dragons. Ye have been warned.  

Based on the incredible work of [Gordian Edenhofer](https://github.com/Edenhofer/minecraft-server).

## Dependencies
- bash
- awk
- sed
- sudo -- privilege separation
- tmux -- communication with server
- java -- for Minecraft
- netcat -- listen on the minecraft port for incoming connections while the server is down (optional)
- tar -- take world backups (optional)

## Installation
You will need `git` and `make` to perform the installation below. (Tested on Debian 12)
```
git clone https://github.com/TraderHowell/minecraftd.git
cd minecraftd
make
sudo make install
```

## Roadmap
- A command to automatically download the latest vanilla server.jar and automatically open eula.txt in a text editor for acceptance.
- A command to automatically download and install a .mrpack modpack (probably by passing parameters to [mrpack-install](https://github.com/nothub/mrpack-install)).
