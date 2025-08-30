# sof-sp-gamepark-jail
A sofplus script that strengthens .rcon to allow the admin to force slots into spec. Used to control mis-behaving players.

## Installation
put the script into sofplus/addons directory of the sof server.  
Move this line into spf_sv_rcon.func inside .rcon function. `set ~command_jail "spf_sv_rcon_jail;1;.rcon jail <slot>"`  
Edit spf_sv_gamepark.func to include jail inside the line: `set ~commands "red,restart,say,spec,spectator_password,status,swap,timelimit,unmute,unpause,weapons,shuffle,jail"`