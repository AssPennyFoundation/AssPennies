# AssPennies (ASS)

![AssPennies](http://i.imgur.com/X4coDlS.png)

## What are AssPennies?
Every time a penny passes through your hands, stick it up your ass... and then spend it. You don't just stick 'em up your ass, you spend them. It's a long-term strategy.

Check [this](https://www.youtube.com/watch?v=f9aM_dT5VMI) out if you don't get the joke.

Seriously though, AssPennies are a scrypt cryptocurrency built with love on a foundation of confidence and having the upper hand.

## How to get AssPennies
Until an exchange gets its shit together and starts trading AssPennies, there are three ways to get them:

* CPU mine with ``asspenniesd``
* ATI/AMD mine with ``cgminer`` 3.7.2: http://ck.kolivas.org/apps/cgminer/3.7
* Nvidia mine with ``cudaminer``: https://github.com/cbuchner1/CudaMiner


### Let's talk numbers
* 12,012,000 total AssPennies will be created (8 times the population of Nebraska)
* Blocks are mined every 12 minutes
* Block reward is 25 AssPennies
* Difficulty is readjusted every 4 hours
* 3,000 AssPennies are mined every day

## Building the AssPennies wallet
The AssPennies wallet has been successfully compiled on Ubuntu 16.04, OS X 10.11 (El Cap), and Windows XP.

Windows binaries can be downloaded for [each release](https://github.com/AssPennyFoundation/AssPennies/releases/latest), or you can use the [EasyWinBuilder](contrib/easywinbuilder) .bat files to download the dependencies, compile the dependencies, and then compile the daemon and Qt client.

### OS X 10.11 El Capitan build process:

	brew install boost
	brew install berkeley-db
	brew install openssl
	brew link openssl --force
	brew install miniupnpc

	cd ~/AssPennies/src
	make -f makefile.osx

	cd ~/AssPennies
	qmake -spec macx-g++ asspennies-qt.pro
	make

### Linux/Ubuntu build process:

	sudo add-apt-repository ppa:bitcoin/bitcoin
	sudo apt-get update

	sudo apt-get install
		build-essential \
		libdb5.3++-dev \
		libssl-dev \
		libminiupnpc-dev \
		libboost1.58-dev \
		libboost-chrono1.58-dev \
		libboost-date-time1.58-dev \
		libboost-filesystem1.58-dev \
		libboost-program-options1.58-dev \
		libboost-regex1.58-dev \
		libboost-system1.58-dev \
		libboost-thread1.58-dev

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

[![Ass Pennies on YouTube](http://i.imgur.com/8tIuBCL.jpg)](https://www.youtube.com/watch?v=DO1Q7F23DxM)

AssPennies is released under the terms of the MIT license.
See [COPYING](COPYING) for more information or see http://opensource.org/licenses/MIT.
