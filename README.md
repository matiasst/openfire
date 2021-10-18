# openfire
openfire spark on docker 

# Installation

docker run --name openfire -d --restart=always \
--publish 9090:9090 --publish 5222:5222 --publish 7777:7777 \
--volume /srv/docker/openfire:/var/lib/openfire \
696154315/openfire:4.6.2

localhost:9090
