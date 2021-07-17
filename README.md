# laravel-backend app

## Description

```bash

    laravel 8 
    php 8 
    docker 
    sail

```
## Commnds

```bash

    alias sail='bash vendor/bin/sail'


     copy .env.dev .env
    # Use command to run docker sail
    APP_PORT=3001 vendor/bin/sail up
    
```
## Fix docker containers 

```bash

    # Use command to run docker sail
    APP_PORT=3001 vendor/bin/sail down -volumes
    vendor/bin/sail up -build
    
```

## add image storage 

```bash

    # Use command to run docker sail
    php artisan storage:link
    
```
## add image storage 

```bash
#use mariadb
DB_CONNECTION=mysql
DB_HOST=mariadb
    
```


## implement faster sail

```bash
run docker and move repo code of laravel to linux engine like below
\\wsl$\Ubuntu-20.04\home\{user}\laravelfolder
```


## fix laravel storage 

sudo chown -R $USER:www-data storage
sudo chown -R $USER:www-data bootstrap/cache

chmod -R 775 storage
chmod -R 775 bootstrap/cache

sudo chmod -R 777 storage :

http://35.223.238.193:3001/storage/upload_ckeditor/nuxt_1623175284.jpg


php artisan storage:link 

which http-server
$ pm2 start /usr/bin/http-server --name my-file-server -- -p 8080 -d false


pm2 start '/root/.nvm/versions/node/v14.17.0/bin/http-server dist -p 3000'  --name nuxtbombshell


http://localhost:3000/login?state=wSne0kJH0g&code=4%2F0AY0e-g5LXu0PEaqT8ggC7EfitpOMVdjZe5JBucWv7RYI16Zy7-y4tAVv5imNrjnj5xamaw&scope=email%20profile%20openid%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fuserinfo.profile%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fuserinfo.email%20https%3A%2F%2Fwww.googleapis.com%2Fauth%2Fgmail.metadata&authuser=0&prompt=consent


    alias sail='bash vendor/bin/sail'


nano ~/.bash_aliases
add to file alias sail='bash vendor/bin/sail'
exit
source ~/.bash_aliases
#   b a c k e n d _ v u e  
 