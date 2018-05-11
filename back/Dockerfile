FROM node:8

RUN npm install pm2 -g

RUN mkdir /src
WORKDIR /src
ADD ./back/package.json /src/package.json
ADD ./back /src
RUN npm install

EXPOSE 3000

CMD ["pm2-runtime", "bin/www"]
