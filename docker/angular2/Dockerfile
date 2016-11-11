FROM node:6.9.1-slim

ENV CLI_VER 1.0.0-beta.19-3

RUN npm install -g angular-cli@$CLI_VER && npm install -g node-gyp
RUN npm cache clean
RUN mkdir -p /data/ && cd /data  && ng --version
RUN ng new demo -sn && cd demo
RUN ng init



