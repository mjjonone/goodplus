FROM eclipse-temurin:17-jre-alpine

EXPOSE 3000
WORKDIR /home

COPY run.sh /home
RUN apk update &&\
    apk add --no-cache curl 

CMD [ "sh", "/home/run.sh" ]