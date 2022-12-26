# configure-firewall-ufw-linux-vm
Configure a UFW firewall on a linux virtual machine

- sudo ufw status
- First disable: sudo ufw disable
- Enable: sudo ufw enable
- Setup default: no incoming allwed, outgoing allowed: 
  - sudo ufw default deny incoming
  - sudo ufw default allow outgoing
- Allow SSH: sudo ufw allow ssh
- Enable: sudo ufw enable
- Allow OpenSSH access
  - sudo ufw app list
  - sudo ufw allow OpenSSH
  - sudo ufw enable
  - sudo ufw status



References

- https://www.digitalocean.com/community/tutorials/how-to-setup-a-firewall-with-ufw-on-an-ubuntu-and-debian-cloud-server

- https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-22-04 

- https://www.digitalocean.com/community/tutorials/ufw-essentials-common-firewall-rules-and-commands
