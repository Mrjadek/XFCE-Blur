# XFCE Picom Dotfiles

Picom dotfiles for XFCE, with blur and rounded corners

# Install Picom:

openSUSE:
```
sudo zypper in picom
```
Arch:
```
sudo pacman -S picom

```
Debian:

```
sudo apt install picom
```
Ubuntu doesn't has it in the repositories, so go build it yourself

# Install the dotfiles

Clone this git repo:
```
git clone https://github.com/Mrjadek/XFCE-Blur.git
```
cd Into it:
```
cd XFCE-Blur
```
Copy the dotfiles:
```
cp -r picom.conf ~/.config/picom/

```
If picom doesn't exist
```
mkdir ~/.config/picom
```
# Launch Picom and Add to autostart

```
picom &

```
Add it to autostart in xfce4-settings-manager

