#finPipeline

finPipeline is a VFX pipeline for small team and studio use on commercial and film produciton.  We believe a successful pipeline is based on providing a flexible structure that enables consistency of delivery in the face of changing creative and technical demands.  Our goal is to provide a framework of tools to help in this process.

###Dependencies
Here's the bare minimum of dependencies to get started:
* Bash Shell
* Python 2.7
* pip
* shyaml
* A package management program (Homebrew, Cygwin, apt-get, etc)

###Boxen
If you're on OSX we highly suggest using Boxen puppet modules to do an initial install of required software.  You can find our fork of https://github.com/boxen/our-boxen which has additional software installs we use in film production here:
https://github.com/extrinsicmedia/finboxen

###Installation

Instructions for installation of software requirements for the environment can be found in the /finPipeline/os directory.

Basic installation using Mac OSX 10.7.5 as example:

1. Fork or clone finPipeline to your shared system server.  For example: 
    `cd /mnt/server/systems/ && git clone https://github.com/extrinsicmedia/finPipeline.git`

2. Copy the config file to your $HOME directory and change the paths for your server:
    `cp finPipeline/config/finpipeline.yaml $HOME`

3. Run the following to source the unix_config_global.sh in your .bashrc file:
    `echo "source /mnt/server/systems/finPipeline/bash/unix_config_global.sh" >> ~/.bashrc`

4. Use /finPipeline/python/fin/fin/fileOps/dirOps.py to create your job folders.

5. Log any errors as Github issues or email for help.


If you find this code useful, feel free to tip: https://www.gittip.com/extrinsicmedia


