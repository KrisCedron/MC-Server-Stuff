## FIRST TIME SETUP ##

- open the "START-SERVER.bat" file ("START-SERVER.sh" for mac/linux).
- when prompted to agree to Minecraft's EULA, type "I agree" if you agree, type anything else if you don't.
- if you want to edit the allocated RAM amount, stop the server, open "user_jvm_args.txt" and change the number in "-Xmx4G".
- edit the "server.properties" and "server-icon.png" file to your liking.


## UPDATING THE SERVER ##

- stop the server using "stop" in the server console.
- download the latest server file.
- backup the old server folder. 
- delete "config" and "mods" folders, and the 2 SERVER-START files.
- replace the deleted files with the new versions from the downloaded zip.
- if you made any modifications to some configs (serverutils folder for example), restore them from the backup (at your own risk).
- launch the server with START-SERVER.


## USEFUL COMMANDS ##

- start by giving your self OP rights by typing "/rank add [player_name] op" in the server console.
- you can enable economy and discord chat bot from ServerUtils configs, as well as add ranks and kits.
- /rtp, /rtpnear, and /rtpfar will teleport a player to a random location.
- /sethome to make a waypoint and /home to return to it, /delhome to remove it, /homes for the list, by default players can only have 3 homes max, configurable.
- /claim to claim a chunk, /unclaim to remove the claim, /claimflag to edit permissions inside it, /trust to allow a player to access your claims, by default players can have 24 claimed chunks max, configurable.
- /back to return to where you last teleported from, or where you died.
- /setwarp to create a global waypoint, /delwarp to remove it, by default only OP ranked players can set warps, other can travel to them using /warp warp_name, /warps will show the warps list.
- /tpa to ask a player to teleport to them, /tpahere to ask them to teleport to you, /tpaaccept to accept the request, /tpadeny to reject.
- server admins can use /god and /invsee to manage players.
>> for more info visit: https://elrol.dev/wiki/server-utilities/