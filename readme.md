Home server (Raspberry + external ssd) working on local network

- nextcloud (sync ipad/iphone): OK
- cockpit: OK
- portainer: OK
- (sync kindle): NOK
- pi-hole: NOK
- changer les fichiers /etc/hosts: NOK

To scan local network ips: `$ nmap -sP [ip-address]/24`

## How to launch

- variables and paths to update: 
  - volume paths
  - inventory.ini
  - passwords

`$ ansible-playbook main.yml`
