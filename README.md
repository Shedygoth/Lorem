

1.1Prerequisite:

1.Docker installed  
2.Docker-compose

3.Create $ docker network nginx-proxy (To be able to pass the traffic to Nginx)



1.2 Open the Nginx folder and run it: 
$ docker-compose up -d  (Container with Nginx proxy will be spin up to be able to create a proxy)


1.3 Open the Wordpressabd and run it:

$ docker-compose up -d

1.4 Verify:

$ docker container ps -a (to list the running containers)

Enter in the browser your DNS or IP(public/private) to verify does it working



