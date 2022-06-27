FROM openjdk:8-jdk-stretch
RUN apt-get update && apt-get install git -y && apt-get install maven -y
WORKDIR /home
RUN git clone https://github.com/HardCode-Me/App42
WORKDIR /home/App42
RUN mvn package
CMD /bin/sh
