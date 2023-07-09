# wordpress_docker
Run Wordpress localy in by docker

clone this repo then download wordpress and extract *wordpress* folder inside folder that you cloned.
replace passwords and info that are inside <> in *docker-compose.yml* and *wp-config.php* file

`If you run projects and it do not work, paste *wp-config.php* to *wordpress* folder`

then run this command:

```
docker compose up -d
```

> `Then you can open http://localhost:8000 for wordpress and http://localhost:8080 for phpmyadmin`

for down project:
```
docker compose down --volumes
```

