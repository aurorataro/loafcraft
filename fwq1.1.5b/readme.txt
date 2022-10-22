1. Download https://meta.fabricmc.net/v2/versions/loader/1.18.2/0.14.9/0.11.1/server/jar
2. Drag into main folder of server (with mods folder, config folder etc.), rename to exactly "server.jar" (ensure it isn't named server.jar.jar when file extensions are hidden)
3a. If hosting from a windows machine run the ".bat" script and the server should begin initialising.
3b. If hosting from a linux machine run the ".sh" script (e.g. command "sh startmc.sh" in console).
4. Once server runs, an "eula.txt" will appear. Open it and set it to 'true'.
5. Re-run the server and it should now boot.

Ensure you have properly port-forwarded your ip! This varies wildly based on your internet provider, server host or country so find an online resource to help with this.
To change the allocated RAM, open your relevant startup script in notepad and change the -XMX and -XMS flags from 4G or 6G to whatever amount of gigabytes of ram you prefer.
Don't forget to op yourself through console to perform admin commands ingame 'op YOURNAME'.