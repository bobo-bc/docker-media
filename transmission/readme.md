Transmission-vpn is a fantastic solution for running a download client within the protection and utility of a VPN. It will autokill the download if the vpn breaks. this is the good news. The bad news is that you need to deploy via cli (command line interface).
You see, the VPN requires capabilities add "cap add - net_admin" which is recognized but not through Git or Portainer. 
The workaround is to run the compose file using 

docker stack deploy --compose-file docker-compose.yml transmission

this will run in the swarm and view it in Portainer!!!
