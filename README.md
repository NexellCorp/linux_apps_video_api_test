# linux_apps_video_api_test
This application made for nx-video-api test.

This application testd in following environment.
	CPU : NXP4330, NXP3220
	Package : Nexell yocto(sumo) package.
	Board : Nexell convergence board for NXP4330, Nexell evb board for NXP3220

How to build
	1. sourcing compile environment.
		#> source /opt/poky/2.5.1/environment-setup-cortexa9hf-neon-poky-linux-gnueabi
	2. autogen & configure & compile
		#> ./autogen.sh
		#> ./configure --host=arm-poky-linux-gnueabi- --prefix=$SDKTARGETSYSROOT/usr
		#> make

ToDo
	1. Remove src/include directory and files.
	   We will be remove src/include/linux direcotry when tool-chanin includes kernel uapi files.
