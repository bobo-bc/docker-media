Cloudflare tunnel is how you host locally without opening ports on your router exposing your internal network to bad actors. I have not been able to deploy through repository sucessfully so I do so within Portainer or command line interface (CLI) To run via CLI:
The secure bit is becuae I use secrets function within docker swarm. 
docker stack deploy --compose-file cloudsecure.yml tunnel

this will run in the swarm and view it in Portainer!!!
