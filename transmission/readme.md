Transmission-vpn is a fantastic solution for running a download client within the protection and utility of a VPN. It will autokill the download if the vpn breaks. this is the good news. The bad news is that it does not work in a swarm. 
You see, the VPN requires access to /dev/tun which requires a host access. 
The workaround is to run the compose file using 

docker compose up -d

this will run as a single docker instance on the node you run the command and not a member of the swarm. 

You can stall view and manage the container in your swarm portainer. 
