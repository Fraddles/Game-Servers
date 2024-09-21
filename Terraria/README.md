Our first attempt at running a Terraria server was using Tshock on an RPi3...

https://ikebukuro.tshock.co/

After a couple of false starts with incompatible libraries and versions;
* The first attempt failed with arm64 compatibility issues...
* The second attempt (on 32bit) worked, but turned out to be incompatible with the current version of the game...

We came across this great set of instructions which did the trick... https://pimylifeup.com/terraria-server-linux/
Although initially we had issues connecting to the server, even though it was working, we soon discovered that the power supply we had on the Pi was inadequate.  After rectifying this issue we had a fully functional Terraria server!
