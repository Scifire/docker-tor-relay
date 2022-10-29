# docker-tor-relay
Simple docker container for a tor relay node.

Based on: https://tor.stackexchange.com/questions/19949/how-do-i-set-up-a-tor-relay-as-a-docker-container

New build will be triggert on commit.

[Compose file](docker-compose.yaml) can be used to start the container   
`docker-compose up -d`

[torrc](docker/conf/my-relay/torrc) file will be mounted into the container as RO and can be adjusted as needed

