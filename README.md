# demo_containers-nginx-star_wars_themed
This is a demonstration repository of building containers utilizing a star wars theme with Nginx.

## Build new BabyYoda image
```
git clone
cd docker/nginx/StarWars/BabyYoda
docker build -t nginx_starwars_babyyoda .
```

## Run container locally with interactive shell
```
docker run -it nginx_starwars_babyyoda bash
```

## Run container locally with port 8080 to 80 binding
```
docker run -d -p 8080:80 nginx_starwars_babyyoda
```
