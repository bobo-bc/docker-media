Transmission-vpn does not work in a swarm. VPN requires access to /dev/tun which requires a host access. 
The workaround is to run the compose file using 

docker compose up -d

this will run as a single docker instance on the node you run the command and not a member of the swarm. 

You can stall view and manage the container in your swarm portainer. 
