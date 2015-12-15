
This is to be used with overlay networking:

`docker-compose --x-networking up -d`

Scale up:

`docker-compose --x-networking scale voting-app=2`

Note: if using interlock as a load balancer to load balance these apps, you'll need to adjust the hostnames appropriately and manage them somehow (local host file entry, real DNS entry, DNSmasq, etc)
