# AIC8800DC
Linux driver for AICSemi AIC8800DC, ID a69c:88de

## Usage
```bash
# install setup files
chmod +x install_setup.sh
sudo ./install_setup.sh

# if in a virtual machine, execute this command before install driver
# modprobe cfg80211

# build kernel module
cd drivers/aic8800
make
sudo make install

# load kernel modules
sudo modprobe aic8800_fdrv
sudo modprobe aic_load_fw
```
