# Sourcebans ULX Support
Another implementation of SourceBans in to a ULX module


Configure everything you need in addons/anotherulxsbanmodule/lua/ulx/modules/sban.lua


1) Downloaded the Latest Ulib (2.63) + ULX (3.73) and added them to /addons. https://ulyssesmod.net/downloads.php
2) Downloaded your module and edited the sban.lua file for the credentials, and uploaded to /addons and /lua respectively
3) Downloaded gmsv_tmysql4_linux.dll 1.02 and added it to /lua/bin. https://github.com/bkacjios/gm_tmysql4/releases
4) Added the server to SourceBans and added the variable (with the serverID) ulx_sban_serverid to the server.cfg.

Should see the following :   [MYSQL] Connected user:db@ip:port successfully.


Edit the following to correct sql settings:
addons/anotherulxsbanmodule/lua/ulx/modules/sban.lua
