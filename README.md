# AIC8800DC
Linux driver for AICSemi AIC8800DC, ID a69c:88de

## Usage
```bash
chmod +x install_setup.sh
./install_setup.sh

# if in a virtual machine, execute this command before install driver
# modprobe cfg80211

cd drivers/aic8800
make
make install
```
