Ubuntu 20.04 Focal Fossa
Systemd

cp usbkill.service /etc/systemd/system
sudo chmod 664 /etc/systemd/system/usbkill.service
sudo systemctl daemon-reload
sudo systemctl enable usbkill.service
