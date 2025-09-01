# MCpi5Server
This is how I've set up my minecraft server using paperMC on my raspberryPI5.

I also use the plugins with the base configuration: chunky and SimpleVoiceChat.

# Requiremnts
I used java 24, you can try with different versions if you want but I can't guarantee it will work. 

In order to use the script you simply have to download the paperMC version of your choise and rename it to paper.jar in the same forlder of the script.

# How to use
You can simply launch the command ./server_start on your raspberrypi and enjoy.

# Pregenerate 
To pregenerate the world so I expirience less lag during gaming sessions I used those chunky comands in the server's terminal (after staring it):

> chunky shape circle

> chunky radius 5000

> chunky world overworld

> chunky start

> chunky world world_nether

> chunky start

> chunky world world_the_end

> chunky start
