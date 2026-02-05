setup_GLPI
----------
Setting up GLPI using Docker


### Steps
1. Pull docker image of GLPI
```bash
docker pull glpi/glpi:11.0-nightly
```

2. Create a directory for the stack
```bash
mkdir glpi-stack
cd glpi-stack/
```

3. Run docker compose
```bash
docker compose up -d
```



4. If you want to stop and restart the stack
```bash
docker compose down
docker compose stop
docker compose start
docker compose up -d
docker compose ps
curl -v http://localhost:8020
curl -v http://localhost:8080
```



# Links
- [Image Docker](https://hub.docker.com/r/glpi/glpi)
- [Instruction for Docker Compose](https://help.glpi-project.org/tutorials/procedures/running_glpi_on_docker)
- [GLPI](http://localhost:8080)
- [tutorial](https://www.youtube.com/watch?v=lqVI5V727GU&list=PLBzBQP55u1SXavOFJxGk0zKGgC6dAtq4g)