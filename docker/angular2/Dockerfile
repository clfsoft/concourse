FROM node:6.9.1

ENV CLI_VER 1.0.0-beta.19-3

RUN npm install -g angular-cli@$CLI_VER
RUN mkdir -p /data/ && cd /data && ng new angular2 &&  mv angular2/node_modules . && rm -rf angular2
