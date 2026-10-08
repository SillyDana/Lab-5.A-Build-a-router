sysctl net.ipv4.ip_forward
net.ipv4.ip_forward = 0
sysctl -w net.ipv4.ip_forward=1
sudo nano /etc/sysctl.conf
net.ipv4.ip_forward = 1
sysctl -p
sudo reboot
net.ipv4.ip_forward = 1
sudo ip routeadd 10.10.20.0/24 via 10.10.10.1 dev enp0s9
ip route
10.10.20.0/24 via 10.10.10.1 dev enp0s9
