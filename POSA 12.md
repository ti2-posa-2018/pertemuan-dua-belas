# Manajemen Software dan Repositori di Linux

![Linux](https://i.imgur.com/7tQ9cY4.jpg)

### Ubuntu Software Center

##### Install Software
1. Buka **Ubuntu Software Center** atau **Software Center** atau **Software**.
2. Ketik **VLC**.
3. Klik **Install**.

##### Uninstall Software
1. Buka **Ubuntu Software Center**.
2. Ketik **VLC**.
3. Klik **Remove**.

### Apt atau Apt-get

##### Update Daftar Repositori
1. Perintah meng-update repositori: `sudo apt update`

##### Install Software
1. Perintah meng-install software: sudo apt install vlc

##### Uninstall Software
1. Perintah meng-uninstall (Remove) software: `sudo apt remove vlc`
2. Perintah meng-uninstall (Purge) software dan konfigurasi: `sudo apt purge vlc`

##### Download Software tanpa Install
1. Mendownload Software tanpa Install: sudo apt download vlc

#### Query Cache APT
1. Mencari suatu software: `sudo apt search vlc`
2. Melihat informasi software: `sudo apt show vlc`

##### Update, Upgrade, Dist-Upgrade
1. Update: Memperbarui informasi software.
2. Upgrade: Menginstall software terbaru.
3. Dist-Upgrade: Menginstall Sistem / Kernel Baru.

### DPKG

##### Install Software
1. Download Skype: [Skype](https://www.skype.com/id/get-skype/)
2. Install Skype: `sudo dpkg -i nama-software-teamviewer`

##### Uninstall Software
1. Perintah meng-uninstall Software: `sudo dpkg -r skype`

### Mengubah Server Repositori
1. Buka **Software & Updates**
2. Pada Window **Ubuntu Software**, pilih Download from.
3. Klik other - Indonesia - kambing.ui.ac.id
4. Klik Choose Server