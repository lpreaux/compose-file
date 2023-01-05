# Apache Guacamole

[Official Site](https://guacamole.apache.org/)

Config of my guacamole instance.

## guacamole.yml

Connect to an external postgres(v13) db that is in another stack and accessible by a specific docker network.

> `POSTGRES_PASSWORD: <MDP>` : `<MDP>` à définir

> ⚠️ The db needs to be configured and initialized before run this
> config : [official doc](https://guacamole.apache.org/doc/gug/jdbc-auth.html)
> ```
> POSTGRES_DATABASE: guacamole
> POSTGRES_USER: guacamole
> ```

No port expose. Redirection from an nginx instance (manage
with [nginx-proxy-manager](https://hub.docker.com/r/jc21/nginx-proxy-manager))
on the nextcloud container default port (80) through a docker network called *lofgplv.fr*