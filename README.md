# WindowsGSM.REM
🧩WindowsGSM plugin that provides REM Dedicated server

## PLEASE ⭐STAR⭐ THE REPO IF YOU LIKE IT! THANKS!

### Notes
- Please start the server once, then look into serverfiles\RemSurvival\Saved\Config\WindowsServer\ServerConfig.ini for your serversettings.
- ServerName and ServerPassword are highly recommended to be changed
- Thought about generating the file with the plugin, but for early access games that can be bad, as in that case new options are ignored. 

### WindowsGSM Installation: 
1. Download  WindowsGSM https://windowsgsm.com/ 
2. Create a Folder at a Location you wan't all Server to be Installed and Run.
3. Drag WindowsGSM.Exe into previously created folder and execute it.

### Plugin Installation:
1. Download [latest](https://https://github.com/Raziel7893/WindowsGSM.REM/releases/latest) release
3. Either Extract then Move the folder **REM.cs** to **WindowsGSM/plugins** 
    1. Press on the Puzzle Icon in the left bottom side and press **[RELOAD PLUGINS]** or restart WindowsGSM
4. Or Press on the Puzzle Icon in the left bottom side and press **[IMPORT PLUGIN]** and choose the downloaded .zip

### Official Documentation
🗃️ https://rem-survival.fandom.com/wiki/Dedicated_Servers

### The Game
🕹️ https://store.steampowered.com/app/574180/Rem_Survival/

### Dedicated server info
🖥️ https://steamdb.info/app/1141420/info/

### Port Forwarding (YOU NEED THIS, TO BE ABLE TO CONNECT FROM THE INTERNET(only for servers/pcs at home):
- If You don't know How: portforward.com
- 27015 UDP - Default QueryPort
- 7777 UDP - Default Game Port

### Files To Backup
- Save Gane (You could only save serverfiles/REM/Saved , but that includes many big logs)
  - WindowsGSM\servers\%ID%\serverfiles/Saved
- WindowsGSM Config
  - WindowsGSM\servers\%ID%\configs

### Available Params
All these params are automatically set by WGSM and can be changed via Edit Config Window (don't edit the config Windowsgsm.ini manually)
- MultiHome=176.57.135.59
- Port=7777
- QueryPort=27015

 All other settings see next paragraph

### Config
- to adjust configs either bo to Server Files (clock on Browse => Server Files), got to Saved\Config\WindowsServer. 
  - the files Game.ini and ServerConfig.ini should contain the configs
- change add variables to WindowsGSM by clicking Edit Config and modifing the last box Server Start Param


### Not having an full IPv4 adress ( named CCNAT or DSL Light )
No game or gameserver supports ipv6 only connections. 
- You need to either buy one (most VPN services provide that option. A pal uses ovpn.net for his server, I know of nordvpn also providing that. Should both cost around 7€ cheaper half of it, if your already having an VPN)
- Or you pay a bit more for your internet and take a contract with full ipv4. (depending on your country)
- There are also tunneling methods, which require acces to a server with a full ipv4. Some small VPS can be obtained, not powerfull enough for the servers themself, but only for forwarding. I think there are some for under 5€), the connection is then done via wireguard. but its a bit configuration heavy to setup) 

Or you connect your friends via VPN to your net and play via local lan then.
Many windowsgsm plugin creators recommend zerotier (should be a free VPN designated for gaming) , see chapter below (or tailscale, but no howto there)

## How can you play with your friends without port forwarding?
- Use [zerotier](https://www.zerotier.com/) folow the basic guide and create network
- Download the client app and join to your network
- Create static IP address for your host machine
- Edit WGSM IP Address to your recently created static IP address
- Give your network ID to your friends
- After they've joined to your network
- They can connect using the IP you've created eg: 10.123.17.1:7777
- Enjoy

### Support
[WGSM](https://discord.com/channels/590590698907107340/645730252672335893)

### Give Love!
[Buy me a coffee](https://ko-fi.com/raziel7893)

[Paypal](https://paypal.me/raziel7893)

### License
This project is licensed under the MIT License - see the <a href="https://github.com/raziel7893/WindowsGSM.REM/blob/main/LICENSE">LICENSE.md</a> file for details
