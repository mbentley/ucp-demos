
This is to be used with overlay networking:

`docker-compose --x-networking up -d`

`docker-compose --x-networking -f docker-compose-hub.yml up -d`

Scale up:

`docker-compose --x-networking scale voting-app=2`

`docker-compose --x-networking -f docker-compose-hub.yml scale voting-app=2`

Note: if using interlock as a load balancer to load balance these apps, you'll need to adjust the hostnames appropriately and manage them somehow (local host file entry, real DNS entry, DNSmasq, etc)

 - `docker-compose.yml` specifies images that have been pushed to a local DTR for use; can be fairly easily modified
 - `docker-compose-hub.yml` specifies images that have been pushed to Docker Hub
