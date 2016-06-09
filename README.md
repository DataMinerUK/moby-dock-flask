# Dockerised Flask Application

## Getting started

Building the image and running

```bash
git clone https://github.com/DataMinerUK/moby-dock-flask.git
cd moby-dock-flask
docker-compose build mobydock
docker-machine ip # This will give you an IP address you need to access the application on your computer. It should also appear when you first start a Docker terminal
docker-compose rm -f
docker-compose up
```
In a browser go to the [ip of docker machine]:8000. Feed Moby Dock!

Once the image has been built all you need to do to run the app is

```bash
docker-compose up
```
