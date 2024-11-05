FROM alpine

RUN apk add git php
RUN git clone https://github.com/attogram/games
WORKDIR games/_build
RUN php build.php install
EXPOSE 8080
