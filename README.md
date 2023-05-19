Go to where docker compose file is
All commands start with docker-compose
To start services run : docker-compose up
(the above will start the services and create the images and bring them up or start them

Alternatively execute each command individually:

Build the image
Create the containers
start the application

Incase there are several services and wants to apply to one use:
docker-compose up storefront

Stop all containers:
docker-compose down
(The above stops and deletes all running containers)

or docker-compose stop


docker-compose restart
(stops and restarts running containers)
Alternatively
docker-compose stop followed by docker-compose start


HELP
docker-compose --help
(:gives all thesecommands)




