# NetHunter-Termux
Modified version add full kali linux build for armhf architecture. the original is deleted and fix vnc command not found<br />

# How to install

same as the original

<b>1. Download Termux (Do not install in Play store)</b> <br />
You can download it [here](https://github.com/termux/termux-app/releases) , then open termux<br />

<b>2. Update/upgrade repo and packages.</b> <br />

```
apt update && apt upgrade -y
```

<b>3. Install wget</b><br />

```

apt install wget
```

<b>4. Download the nethunter installer</b><br />

```
wget -O install-nethunter-termux https://bit.ly/ajiedev-inkex
```
<b>5. Make installer executeable</b><br />

```
chmod +x install-nethunter-termux
```
<b>6. Run the installer and done!</b><br />

```
./install-nethunter-termux
```

See original code if interested [here](https://gitlab.com/kalilinux/nethunter/build-scripts/kali-nethunter-project/)




