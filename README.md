# RagdollMultimasters
A utility to play 'Ragdoll Masters' over the internet and on different computers.

Ragdoll Masters is an amazing game that I played since childhood, but development has long since stopped.
The problem I found is that it only allows local multiplayer on the same PC.

Therefore I created this application.

It consists of a client and host side in the same jar.


-------------------------------------------

*Description*

Essentially what happens is the hosts screen is mirrored onto the clients using UDP packets and some compression techniques
This allows the stream to be of lower latency than many other screen sharing resources out on the web.

The clients side merely recieves this input and sends the important keys for the game to the host (Even this is compressed although in total it would be 5 bytes).

The application also includes a chat interface and quality variables for slower networks.

---------------------------------------------

*Network requirements:*

Host: 	High upload speeds
			Low Download speeds
Client: 	High Download Speeds
			Low Upload speeds (literally 10 bytes a second will do.)


*Sadly the source code for this project has been lost, but feel free to decompile the .jar

