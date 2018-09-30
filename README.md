# Metabase Docker-compose


This:  https://github.com/dgleba/metabase


## Usage:  

```
cd /mydockerfolder
git clone  https://github.com/dgleba/metabase 
cd metabase
docker-compose up
```

## make database in mysql

```
cd /srv/dkr/392dkr/backend392
make mycrd
```


## Bash aliases

Also use these alias from https://github.com/dgleba/vamp206a/blob/master/a3/32init.sh#L225

- examples..

	```
	echo "alias dkup='docker-compose up'" >>   ~/.bash_aliases
	echo "alias dkd='docker-compose down'" >>   ~/.bash_aliases
	echo "alias dkupd='docker-compose up -d'" >>   ~/.bash_aliases
	echo "alias dkupr='docker-compose  up --build  --force-recreate  '" >>   ~/.bash_aliases
	echo "alias dkupp='docker-compose up -f docker-compose.prod.yml -d'" >>   ~/.bash_aliases
	echo "alias dkps='set -vx; docker images; docker network ls;	docker volume ls;	docker ps -a;	docker ps; set +vx'" >>   ~/.bash_aliases
    ```
	
	

## Access

Access your instance in a browser at `localhost:6052`.
Edit `localhost` to whatever IP or named address your machine is.


