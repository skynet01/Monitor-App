# Quick installation script

## For Standalone installation

### This script will perform full installation of both AppDaemon 4.x and Monitor-App.

These files are for first time install of AppDaemon 4.x, tested on Raspberry Pi 4 with Raspbian Buster, but should work fine on Ubuntu and other Linux versions. You fill find templates of configuration files provided, you will just need to fill in your own information. Description and examples are within the configuration files itself.

### IMPORTANT INFORMATION
> The script is tested in Raspberry only (RPi3 & 4) but should work on most Linux distro's and usernames
***

To execute the script, run following command from your commandline:

`bash -c "$(curl -sL https://raw.githubusercontent.com/Odianosen25/Monitor-App/master/installerscript/install_ad.sh)"`

If you get an error message about Curl, install curl by do `sudo apt-get install curl -y`

***
This folder contain templates of configuration files to get going, descriptions are inside the tempales.
