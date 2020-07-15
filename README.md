# Pi Fan Controller

Raspberry Pi fan controller.

## Description

This repository provides scripts that can be run on the Raspberry Pi that will
monitor the core temperature and start the fan when the temperature reaches
a certain threshold.

To use this code, you'll have to install a fan. The full instructions can be
found on our guide: [Control Your Raspberry Pi Fan (and Temperature) with Python](https://howchoo.com/g/ote2mjkzzta/control-raspberry-pi-fan-temperature-python).

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

### How to install

# The easiest way to install the fan controller scripts is to use our install script. To do so, SSH into your Pi and clone the repository:
git clone https://github.com/Howchoo/pi-fan-controller.git

# Next, install the requirements:

# If pip is not already installed run:
sudo apt install python3-pip

# Install requirements globally
sudo pip3 install -r pi-fan-controller/requirements.txt

# Now, run the install script
# This script installs fancontrol.py which monitors the core temperature and controls the fan.
# Also, it adds a script called fancontrol.sh to /etc/init.d and configures the script to run when the system boots.
./pi-fan-controller/script/install

