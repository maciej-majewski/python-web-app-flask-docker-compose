# python-web-app-flask-docker-compose

## Python web app using Flask and Redis

- **Releases:** <br />
https://pypi.org/project/Flask/

- **Build and run:** <br />
docker-compose build <br />
docker-compose up <br />
*or in deatached mode:* <br />
docker-compose up -d <br />
- Running on http://localhost:8280/ <br />
- Shutdown and cleanup (removes the containers, default network, but preserves the Redis database): <br />
docker-compose down <br />
- Shutdown and cleanup (removes the containers, default network, and the Redis database): <br />
docker-compose down --volumes <br />