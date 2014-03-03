# AssPennies (ASS)
===========

![AssPennies](http://i.imgur.com/X4coDlS.png)

## What are AssPennies?
Every time a penny passes through your hands, stick it up your ass... and then spend it. You don't just stick 'em up your ass, you spend them. It's a long-term stragegy.

Seriously though, AssPennies are a scrypt cryptocurrency built from FooCoin:  
https://github.com/RazorLove/foocoin


## How to get AssPennies
Until an exchange gets its shit together and starts trading AssPennies, there are three ways to get them:

* CPU mine them with the QT client or asspenniesd
* ATI/AMD cards use cgminer 3.7.2: http://ck.kolivas.org/apps/cgminer/3.7
* Nvidia cards use cudaminer: https://github.com/cbuchner1/CudaMiner


### Let's talk numbers
* 12,012,000 total AssPennies will be mined (8 times the population of Nebraska)
* Blocks are mined every 12 minutes
* Block reward is 125 AssPennies
* Difficulty is readjusted every 4 hours
* 3,000 AssPennies are mined every day

## Building AssPennies QT client

	sudo add-apt-repository ppa:bitcoin/bitcoin
	sudo apt-get update
	sudo apt-get install libdb4.8++-dev    
	sudo apt-get install libminiupnpc-dev \
		libboost-dev \
		libboost-chrono-dev \
		libboost-filesystem-dev \
		libboost-thread-dev \
		libboost-date-time-dev \
		libboost-filesystem-dev \
		libboost-system-dev \
		libboost-program-options-dev 

	qmake	
	make

## Ports
RPC: 21000  
P2P: 21007


## You think you're better than me?
You don't pull down 8 figures a year without having it _together_.  
AssPennies is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.


[![Ass Pennies on YouTube](http://i.imgur.com/8tIuBCL.jpg)](https://www.youtube.com/watch?v=DO1Q7F23DxM)
