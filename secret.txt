FROM node:alpine

LABEL maintainer=etienne

ADD app.js .

ENTRYPOINT [ "node", "app.js" ]
