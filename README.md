# MCpi5Server

This is how I've set up my Minecraft server using PaperMC on my Raspberry Pi 5.

I also use the plugins with the base configuration: Chunky and SimpleVoiceChat.

# Requirements

I used Java 24, you can try with different versions if you want but I can't guarantee it will work.

In order to use the script you simply have to download the PaperMC version of your choice and rename it to paper.jar in the same folder as the script.

# How to use

You can simply launch the command ./server_start on your Raspberry Pi and enjoy.

# Pregenerate

To pregenerate the world so I experience less lag during gaming sessions I used these Chunky commands in the server's terminal (after starting it):

chunky shape circle

chunky radius 5000

chunky world overworld

chunky start

chunky world world_nether

chunky start

chunky world world_the_end

chunky start

