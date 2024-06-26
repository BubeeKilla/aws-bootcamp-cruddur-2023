# Week 1 — App Containerization

fleet.linuxserver.io
hub.docker.com

# Build Image
docker build -t backend-flask ./backend-flask

# Check Images
docker images

# Check if docker still runs
docker ps

# Run Image
docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKENDURL='*' backend-flask

# Run in background
docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKENDURL='*' -d backend-flask
