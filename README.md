# Quick-strapi

## prerequisites

For this application you will need docker and docker-compose

## To start

1. copy and rename *env* to *.env* 

2. by default we use a mariadb instance if you wanna use anothertype of database change the part part strapidb in *docker-compose.yml*. Here you can change the port exposed

3. run docker-compose
    
    > docker-compose up -d

4. to stop run 
    
    > docker-compose down

## To change strapi

you can change strapi options in ./app the documentation can be found here : [link](https://strapi.io/documentation/developer-docs/latest/getting-started/introduction.html#what-is-strapi)