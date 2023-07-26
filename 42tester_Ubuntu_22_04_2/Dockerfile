FROM ubuntu:22.04

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install nano git -y
RUN apt-get install build-essential -y
RUN apt-get install xorg x11-apps libxext-dev libbsd-dev valgrind -y
RUN apt-get install binutils -y
RUN apt-get install libreadline8 libreadline-dev -y
RUN apt-get -f install
