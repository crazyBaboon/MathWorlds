Welcome to MathWorlds!

So far, MathWorlds allows you to create a world defined by an implicit relation f(x,y,z,c)=0.
To change the mathematical objects, change the function "int MapgenV5::generateBaseTerrain()"
that is written in MathWorlds-0.4.16/src/mapgen_v5.cpp.

Just compile the game as you would with minetest and then choose 'MathWorlds' in the mapgen menu! Have fun!


/-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-//-*-/
Don't forget to add ''static_spawnpoint = 50,20,0'' to your minetest.conf file or else you will fall into INFINITY!!



Install dependencies. Here's an example for Debian/Ubuntu:
$ sudo apt-get install build-essential libirrlicht-dev cmake libbz2-dev libpng-dev libjpeg-dev libxxf86vm-dev libgl1-mesa-dev libsqlite3-dev libogg-dev libvorbis-dev libopenal-dev libcurl4-gnutls-dev libfreetype6-dev zlib1g-dev libgmp-dev libjsoncpp-dev

For Fedora users:
$ sudo dnf install make automake gcc gcc-c++ kernel-devel cmake libcurl* openal* libvorbis* libXxf86vm-devel libogg-devel freetype-devel mesa-libGL-devel zlib-devel jsoncpp-devel irrlicht-devel bzip2-libs gmp-devel sqlite-devel luajit-devel leveldb-devel ncurses-devel doxygen spatialindex-devel bzip2-devel

Instruction to compile:

1. cd to master directory

2. cmake . -DRUN_IN_PLACE=TRUE && make -j2

3. Go to bin folder and run ./minetest (for more details and options https://github.com/minetest/minetest)


MathWorlds (c) 2017 crazyBaboon
MathWorlds is a fork of Minetest 0.4.16 and is released under the same license of the original work.
