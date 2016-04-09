FROM debian:jessie

ENV DEBIAN_FRONTEND to noninteractive

RUN apt-get update && apt-get -y dist-upgrade && apt-get install -y libuser ca-certificates && apt-get clean
