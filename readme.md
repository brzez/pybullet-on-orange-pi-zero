#Installing pybullet on orange pi zero

First run `setup-mem.sh` script.
It will increase /tmp to 5 gb and create 1gb swap.  
These sizes worked for me. I have armbian running off 32gb sdcard.

Usage `./pybullet-install.sh > out.log | tee out.log`

There probably will be some dependencies missing. The install script might error out a couple times.

Install these dependencies and you should be fine.


Building takes a long time. 
I left it overnight, and it was done in the morning. Not sure on exact amount time it took.
I also used a fan to keep the orange pi cool.
