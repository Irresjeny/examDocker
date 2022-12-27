FROM ubuntu

WORKDIR /

COPY docker-deploy.sh ./

RUN apt update
RUN apt upgrade
RUN apt install -y neofetch
RUN neofetch >> neo.log

ENTRYPOINT ["./docker-deploy.sh"]