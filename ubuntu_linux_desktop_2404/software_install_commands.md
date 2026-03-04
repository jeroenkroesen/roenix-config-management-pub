# Software install commands

Install commands for roenix desktop basic software layer.
  
  

## Apt

```sh
sudo apt install \
audacity \
brasero \
calibre \
cheese \
dconf-editor \
extrepo \
fbreader \
fonts-crosextra-caladea \
fonts-crosextra-carlito \
gimp \
gnome-tweaks \
gpa \
gocryptfs \
gparted \
gthumb \
hexchat \
htop \
inkscape \
keepassxc \
libfuse2 \
libreoffice-l10n-nl \
mpv \
mupdf \
nextcloud-desktop \
scribus \
sound-juicer \
soundconverter \
speedcrunch \
sshfs \
ttf-mscorefonts-installer \
unrar \
vlc \
webp
```
  
  
## Snap

```sh
sudo snap install breaktimer pdfarranger signal-desktop
```
  
  
## Developer Extensions - Apt
  
```sh
sudo apt install \
7zip \
arduino \
build-essential \
cmatrix \
cuetools \
curl \
docker.io \
docker-compose \
fd-find \
ffmpeg \
flac \
fzf \
gimp \
git \
imagemagick \
jq \
neofetch \
obs-studio \
podman \
poppler-utils \
python3-pip \
ipython3 \
python3-venv \
ripgrep \
shntool \
shutter \
tmux \
tmuxp \
virt-manager \
virtualbox \
xclip \
xsel \
zoxide \
zsh
```
  
  
## Developer Extensions - Snap
  
```sh
sudo snap install joplin-desktop drawio sqlitebrowser fx
sudo snap install codium --classic
sudo snap install nvim --classic
sudo snap install astral-uv --classic
sudo snap install kubectl --classic
```
  
  
## Developer Extensions - Python UV
  
```sh
uv tool install frogmouth
uv tool install harlequin
uv tool install --python 3.12 posting
```
  
  
## Developer Extensions - Rust/Cargo
  
Install Rust itself:
```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
  
Cargo installs:
```sh
cargo install --force yazi-build
```
  
  
## NVM custom install
  
Check [Github](https://github.com/nvm-sh/nvm) for latest version command below.
  
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash
```
  
NVM can easily be managed on ZSH using a zsh-plugin.
[Plugin github](https://github.com/lukechilds/zsh-nvm)

To install via an Oh-My-ZSH plugin:
```bash
git clone https://github.com/lukechilds/zsh-nvm ~/.oh-my-zsh/custom/plugins/zsh-nvm
```

Then add `zsh-nvm` to plugins in your `.zshrc` and restart ZSH.
