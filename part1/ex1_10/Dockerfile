FROM ubuntu
RUN apt update && apt install -y curl git nodejs npm 
RUN git clone https://github.com/docker-hy/frontend-example-docker
WORKDIR ./frontend-example-docker
RUN npm install
