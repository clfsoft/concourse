FROM node:6.9.5-slim

ENV CLI_VER 1.0.0-beta.26

RUN npm cache clean  && npm install -g angular-cli@$CLI_VER && npm cache clean && npm install -g node-gyp && npm install -g node-pre-gyp && npm install -g angular-cli@$CLI_VER

RUN ng --help