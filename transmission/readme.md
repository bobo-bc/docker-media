Transmission-vpn is a fantastic solution for running a download client within the protection and utility of a VPN. It will autokill the download if the vpn breaks. The VPN requires capabilities add "cap add - net_admin" which is recognized but not through repository deployment so I run it within portainer or command line interface (CLI)
To run via CLI: 

docker stack deploy --compose-file docker-compose.yml transmission

this will run in the swarm and view it in Portainer!!!
