![pack_instal1](../Images/pack_instal1.png)

We have selected a mirroring_url as we isntall the OS. The mirror adress will be set in for Debian ***/etc/apt/sources.list***/ or for CentOS ***/etc/yum.repos.d***/ .

![pack_instal2](../Images/pack_instal2.png)

***dpkg --info <packet_name.deb>*** command gives us the info of the packet, that is not yet installed, is just in repo. That why the extension of the packet is ***.deb*** .

***dpkg -c <packet_name.deb>*** command gives us the info of the place, on where the packet will be installed. 

***dpkg -i <packet_name.deb>*** command installs the packet. With the usage of the  ***"wildcard * "*** can multiple installation is also possible. 

***dpkg -reconfigure <program_name>*** command will repair the already installed program. 

***dpkg -P <program_name>*** command will prune the already installed program. 

***apt-get install <program_name>*** command install the program from repo. 

***apt-get show <program_name>*** command shows info about to be installed programs. 

***apt-get remove <program_name>*** command removes the already installed program . 

***apt-get purge <program_name>*** command removes the program with all its dependencies and configurations.