# THMHO_ocb - Orion Context Broker
This repository contains the dockerized `orion context broker` that is used for sending context information. This contains a docker file of the orion and mongodb. Mongodb helps in data persistance during the communication.

## Starting up ocb
Launch the Orion Context Broker(OCB) in the docker container with port `1026` exposed.
```
sudo docker-compose up
```
References
  - [Use OCB with docker](https://fiware-orion.readthedocs.io/en/1.3.0/user/docker/index.html)
  - [Database administration](https://fiware-orion.readthedocs.io/en/master/admin/database_admin/index.html)
