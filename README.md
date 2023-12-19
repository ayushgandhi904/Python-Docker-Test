# python-docker

A simple Python app for [Docker's Python Language Guide](https://docs.docker.com/language/python).


How to run & create complete Docker Image.

### Clone or create any repository
In this case, I took from Docker itslef
```
git clone https://github.com/docker/python-docker
```

After, initializing the repository, Run the following commands on CMD
```
docker init
```
After setting up requirement it will create python enviornment (if not exists), local host, etc. to build up with.

Final command to build the imange
```
docker compose up --build
```

After image is build, run on the local host to test it