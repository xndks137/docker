FROM alpine

RUN apk add git npm 
RUN git clone https://github.com/herebefrogs/highway-404
WORKDIR highway-404
RUN npm install

EXPOSE 3000

CMD npm start
