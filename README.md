# ItsRakibRoni
### Wifite_RakibRoni_Installer
### Note:Your Device Must Be Rooted.
## [RakibRoni](https://github.com/rakibroni2468/Wifite_RakibRoni) installer for [Termux](https://termux.com/)
### Setup
```
curl -sSf https://raw.githubusercontent.com/drygdryg/OneShot_Termux_installer/master/installer.sh | bash
```
### Run
Disable Wi-Fi in the system settings and run:
```
sudo python OneShot/oneshot.py -i wlan0 -K
```
### How to update OneShot
To check for updates and update, run the following command:
```
(cd OneShot && git pull)
```
