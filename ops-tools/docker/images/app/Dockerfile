FROM debian

RUN mkdir /app \
	&& apt-get update \
	&& apt-get install default-jre -y \
	&& apt-get install default-jdk -y \
	&& apt-get install maven -y

WORKDIR /app

ENTRYPOINT mvn spring-boot:run
