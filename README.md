# COP4600-P3-FileSystems
Custom file system built in C++ that is compatible with the Linux file system.

To build the library and daemon, we will execute these commands:

	$ tar zxvf wad.tar.gz
	$ cd libWad
	$ make
	$ cd ..
	$ cd wadfs
	$ make
	$ cd ..
 
To run your daemon, we will execute this command:

	$ ./wadfs/wadfs -s somewadfile.wad /some/mount/directory
 
To build another program using your library, we will execute this command:

	$ c++ -o program_name sourcefile.cpp -L ./libWad -lWad
