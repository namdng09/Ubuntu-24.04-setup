# Ubuntu 24.04 setup
Everythings to do after install Ubuntu 24.04 LTS

### 1. Checking for updates
```bash
sudo apt update && sudo apt dist-upgrade -y
```

### 2. Install Extra Media Codecs
```bash
sudo apt install ubuntu-restricted-extras -y
```

### 3. Install Gdebi for Quick Install DEB Package
```bash
sudo apt install gdebi -y
```

### 4. Enable Minimize on Click
```bash
gsettings set org.gnome.shell.extensions.dash-to-dock click-action 'minimize'
```

- ## [Click](https://www.google.com/)
