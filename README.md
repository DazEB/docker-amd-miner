# docker-amd-miner
IN DEVELOPMENT-NEEDS TESTING

AMD miner for Kasm Workspaces

This Dockerfile will install and run a full desktop with AMD GPU drivers installed,

allowing you to mine instantly, from a docker container.

Currently only RX580 has been tested.

To run this container you need to install the desktop streaming platform Kasm Workspaces

https://www.kasmweb.com/

After installing Kasm you can create a new dockerfile and run it with

`sudo docker build -t amdgpu:trm091 -f Dockerfile .`

The script will download and unzip TeamRedMiner 0.9.1

Log into Kasm Admin UI and create a new image

Image name has to be amdgpu:trm091 # You can actually choose any name as you want as long as it's the same as whats in the build command

Other information is not important. Add a logo link from the web. Pick the amount of cores you want and select GPU enabled

See example https://kasmweb.com/docs/latest/how_to/building_images.html



