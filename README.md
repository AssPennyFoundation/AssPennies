# AssPennies (ASS)

![AssPennies](http://i.imgur.com/X4coDlS.png)

## What are AssPennies?
Every time a penny passes through your hands, stick it up your ass... and then spend it. You don't just stick 'em up your ass, you spend them. It's a long-term strategy.

Seriously though, AssPennies are a scrypt cryptocurrency built with love on a foundation of confidence and having the upper hand.

## How to get AssPennies
Until an exchange gets its shit together and starts trading AssPennies, there are three ways to get them:

* CPU mine with the Qt client or asspenniesd
* ATI/AMD mine with cgminer 3.7.2: http://ck.kolivas.org/apps/cgminer/3.7
* Nvidia mine with cudaminer: https://github.com/cbuchner1/CudaMiner


### Let's talk numbers
* 12,012,000 total AssPennies will be created (8 times the population of Nebraska)
* Blocks are mined every 12 minutes
* Block reward is 25 AssPennies
* Difficulty is readjusted every 4 hours
* 3,000 AssPennies are mined every day

## Building the AssPennies Qt client
The Qt client has been successfully compiled on Ubuntu 12.04, and Ubuntu 13.10, and Windows XP.  

Windows binaries can be downloaded for [each release](https://github.com/AssPennyFoundation/AssPennies/releases/latest), or you can use the [EasyWinBuilder](contrib/easywinbuilder) .bat files to download the dependencies, compile the dependencies, and then compile the daemon and Qt client.

###Linux/Ubuntu build process:

	sudo add-apt-repository ppa:bitcoin/bitcoin
	sudo apt-get update
	sudo apt-get install libdb4.8++-dev

__The required miniupnpc and boost library versions are different between Ubuntu 12.04 and 13.10.__

Ubuntu 12.04:

	sudo apt-get install libminiupnpc8-dev \
            libboost1.48-dev \
            libboost-chrono1.48-dev \
            libboost-date-time1.48-dev \
            libboost-filesystem1.48-dev \
            libboost-program-options1.48-dev \
            libboost-regex1.48-dev \
            libboost-system1.48-dev \
            libboost-thread1.48-dev 

Ubuntu 13.10:

	sudo apt-get install libminiupnpc-dev \
            libboost1.53-dev \
            libboost-chrono1.53-dev \
            libboost-date-time1.53-dev \
            libboost-filesystem1.53-dev \
            libboost-program-options1.53-dev \
            libboost-regex1.53-dev \
            libboost-system1.53-dev \
            libboost-thread1.53-dev
     
Ubuntu 14.04:
        sudo apt-get install
            qt4-dev-tools \
            qt4-qmake \
            libdb5.1++-dev \   
            libminiupnpc-dev \
            libcurl4-openssl-dev \
            libboost1.54-dev \
            libboost-chrono1.54-dev \
            libboost-date-time1.54-dev \
            libboost-filesystem1.54-dev \
            libboost-program-options1.54-dev \
            libboost-regex1.54-dev \
            libboost-system1.54-dev \
            libboost-thread1.54-dev

After installing all dependencies:

	qmake
	make

## Ports
RPC: 21000  
P2P: 21007

## Contributing to this project
If you want to contribute to the project: 

* Fork this repo
* Commit changes to your forked repo
* Submit a pull request when your feature or bug fix is ready

## You think you're better than me?
You don't pull down eight figures a year without having it _together_.  
AssPennies is released under the terms of the MIT license. See [COPYING](COPYING)i
for more information or see  
http://opensource.org/licenses/MIT.


[![Ass Pennies on YouTube](http://i.imgur.com/8tIuBCL.jpg)](https://www.youtube.com/watch?v=DO1Q7F23DxM)
