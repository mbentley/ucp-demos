`docker-demo/` - Basic single container application in go; easily scaled

`docker-demo-db/` - Multi container version of above; has a database portion.  Not tested with multi-host networking

`interlock/` - Starts interlock on UCP; needs IP changed in compose file but should work out of the box besides that

`multi-container/` - Random multi container application that doesn't really interact, will just start 3 services that don't talk to each other

`voteapps/` - Voting application; images have to be built currently and named accordingly; came from https://github.com/docker/example-voting-app
