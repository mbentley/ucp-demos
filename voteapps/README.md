
This is to be used with overlay networking:

`docker-compose up -d`

Scale up:

`docker-compose scale voting-app=2`

Note: if using interlock as a load balancer to load balance these apps, you'll need to adjust the hostnames appropriately and manage them somehow (local host file entry, real DNS entry, DNSmasq, etc)

 - `docker-compose.yml` compose v2 format; specifies images that have been pushed to Docker Hub
