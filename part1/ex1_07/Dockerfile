FROM ubuntu

RUN apt-get update && apt-get install -y curl
WORKDIR /root
COPY website.sh ./

CMD ["/root/script.sh"]
