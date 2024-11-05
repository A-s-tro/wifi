 TP-Link TL
sudo apt install -y realtek-rtl8188eus-dkms #install driver
sudo wifite
lsusb
sudo wifite --kill
sudo shutdown -r now
sudo systemctl restart NetworkManager
sudo wifite --dict astro.txt --kill





