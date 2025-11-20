## Guide for Internet Games Server (IGS) for Windows ME/7/XP usage and setup

Hi there, another GitHub traveler! Today I will be your guide for connecting and starting a server on [IGS](https://github.com/provigz/ZoneInternetGamesServer), a
MSN Zone Internet Games revival.

> [!TIP]
> To use the guide properly, be sure you do it with Windows 7 Games for Windows 10 installed and ZIGS in folder on C or external drive like D or E

## Launching the server

To launch the server, download the version for your CPU arch from the IGS GitHub link at the top
Then unzip the archive downloaded from releases to some folder at one of your internal/external drives

Then, go to the folder and launch InternetGamesServer.exe, if you do not run it on a VPS/VDS and you run it on your self-host PC, then also reccomended
to use software like Hamachi or Radmin VPN

## Connecting to the server

To connect to your or anothers server, go to the directory of your server EXEC in CMD and type "dllinjector -c"
If one of games (e.g. Internet Checkers) is launched, window will appear from the game in the taskbar

In the window, you should put 'localhost' or IP of ZIGS server you want to connect to, port is unnecesary to enter yours, it always listens on Zone's default port

## Commands and their usage

If you are the hoster of the server and you found cheaters (if there are cheats for MSN Zone IG's lol :skull:) or cyberbullies, these commands might help you:
If found bots, cheaters (:skull:) or bullies, use one of these

`lc` - Lists all connected to the server sockets and their IPs
`lm` - List all match sockets with players and their IPs
`k {ip}` - Kick one of connected IP sockets like `k 192.149.139.23`
`b {ip}` - Ban one of connected IP sockets
`u {ip}` - Remove socket from the banlist

## Culmination

For now, thats all!

I will research the server and it's abilities more on now but still this guide may not get something majoringly new
because thats based off 2.0 version of ZIGS.. beta :3

## With that, how does ZIGS work in super simple words?

ZIGS is Zone Internet Games Server's revival, made because of MSN Games closing on July 31, 2019

And how was ZIGS made? I can't really say the truth but my guess is reverse engineering or protocol recreation

So, PC -> ZIGS -> LAN/WLAN -> Gayming time :3

(i couldnt explain more sry :sob:)
