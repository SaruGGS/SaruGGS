
apt-get update 

apt-get install -y sudo

usermod -aG sudo gabriel

nano /etc/sudoers

gabriel ALL=(ALL:ALL) ALL

Fijamos la direccion IP: 

sudo nano /etc/network/interfaces

cp /etc/network/interfaces /etc/network/interfaces.bk

  address 10.109.99.21/24
  gateway 10.109.0.1

![2023-09-15_13-11](https://github.com/SaruGGS/SaruGGS/assets/93264560/372af05f-6aab-424c-9dfe-a4c975ee52d3)
![2023-09-15_13-10](https://github.com/SaruGGS/SaruGGS/assets/93264560/49050c0d-527c-4aac-929e-160c9c222305)

