Home server (Raspberry + external ssd) working on local network

- nextcloud (sync ipad/iphone): OK
- cockpit: OK
- portainer: OK
- (sync kindle): NOK
- pi-hole: NOK
- changer les fichiers /etc/hosts: NOK

To scan local network ips: `$ nmap -sP [ip-address]/24`

## How to launch

- files to update before (custom environment variables): 
  - services/nextcloud/docker-compose.yml
  - services/pihole/docker-compose.yml

`$ ansible-playbook main.yml`