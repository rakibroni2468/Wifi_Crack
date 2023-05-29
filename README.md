# ItsRakibRoni
### Wifite_RakibRoni_Installer
### Note:Your Device Must Be Rooted.
## [OneShot](https://github.com/drygdryg/OneShot) installer for [Termux](https://termux.com/)
### Setup
```
pkg update && pkg upgrade
pkg install git python

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
