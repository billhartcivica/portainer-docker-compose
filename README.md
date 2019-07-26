# Docker-Compose file for a basic Portainer deployment

Portainer is a management system for overseeing, monitoring and maintaining your Docker or Docker-Swarm
deployments. Easy to deploy, it provides an easy, graphical method of controlling your Docker estate.

- Start by installing Docker on your system (eg: yum -y install docker-ce or apt-get install docker).
- Install docker-compose (ref: https://docs.docker.com/compose/install/)
- Clone this repo onto your system.
- Create a folder on your host systerm: '/opt/portainer'.
- Ensure the line in the volumes section of the docker-compose file referring to your local docker.sock
file is correct.
- Start the instance by running 'docker-compose up -d' from the cloned repository.
- Point your browser to the hostname or IP of your Docker host on port 9000 (http://host-ip-addr:9000).
- You will be prompted to change the Portainer 'admin' password - set this to your preferred option.
- Er...
- That's it...
