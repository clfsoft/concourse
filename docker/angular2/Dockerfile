FROM aucnet4dev/angular2-cli

RUN ng new demo -sn -sg -dir /data/demo && cd /data/demo  && npm install && ls node_modules/ -ll  && ng build && cd /data && mv demo/node_modules . && rm -rf demo




