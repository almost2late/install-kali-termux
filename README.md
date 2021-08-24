# install-kali-termux
### Custom Kali installation based on the minimal file-system of the official nethunter repositories from Offensive Security, in termux with a rooted device.
### More functions were added than in the script provided by offensive security and I will add more when the time comes.

<p align="center">
  <img width="460" height="300" src="https://github.com/ind3p3nd3nt/install-kali-termux/raw/master/Annotation%202021-08-24%20155445.png">
</p>


#### Open termux and paste this code to install kali on it:
```bash
apt update && apt install wget -y
wget -O install_kali https://git.io/JUnAD 
chmod +x install_kali
./install_kali
```
#### Short link to this page:
https://is.gd/kalitermux

## NEW:
### Support for x86 and AMD64 added; now you can install kali in an Android emulator!
