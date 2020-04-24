FROM ubuntu
RUN apt update && apt install -y curl git nodejs npm 
RUN git clone https://github.com/docker-hy/backend-example-docker
WORKDIR ./backend-example-docker
RUN npm install
EXPOSE 8000
