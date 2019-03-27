# APP BOOTSTRAP
### DEV DNS

### Setup info
1.  `source .env`
2.  `docker network create ${REVERSE_PROXY_NETWORK}`
2.  `docker-compose up -d`
3.  Go to `http://traefik.docker.devweb`

You can update the `.env` file to change base domain name etc.
_PS_ Make sure docker and docker-compose are installed on your 
computer.
* [docker installation]('https://docs.docker.com/install/linux/docker-ce/ubuntu/').
* [docker-compose installation]('https://docs.docker.com/compose/').

Voila !
Enjoy (:) !! 