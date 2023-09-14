
apt-get update 

apt-get install -y sudo

usermod -aG sudo gabriel

nano /etc/sudoers

gabriel ALL=(ALL:ALL) ALL

Fijamos la direccion IP: 

sudo nano /etc/network/interfaces

cp /etc/network/interfaces /etc/network/interfaces.bk

  address:10.109.99.21/24
  gateway:10.109.0.1

![2023-09-14_13-47](https://github.com/SaruGGS/SaruGGS/assets/93264560/334d3430-2bb0-46b9-aaec-edc5da55da8e)
