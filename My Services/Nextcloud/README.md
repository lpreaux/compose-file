# Nextcloud

[Official Site](https://nextcloud.com/)

Config of my Nextcloud instance

## nextcloud.yml

Nextcloud v25

Connect to an external mysql db that is in another stack and accessible by a specific docker network.

> `MYSQL_PASSWORD= <MDP>` : `<MDP>` à définir

No port expose. Redirection from an nginx instance (manage with [nginx-proxy-manager](https://hub.docker.com/r/jc21/nginx-proxy-manager))
on the nextcloud container default port (80) through a docker network called *lofgplv.fr*