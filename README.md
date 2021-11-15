Build the container with: `docker build -t presentation:latest .`
Run the container with `docker run -p 3000:3000 --mount type=bind,source="$(pwd)"/src,target=/app/src presentation:latest`

OR

Just us docker compose: `docker-compose up`