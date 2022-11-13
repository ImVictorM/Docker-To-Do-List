FROM node:14-alpine

EXPOSE 3000
WORKDIR /front-end
COPY . .
ADD node_modules.tar.gz .
RUN npm i
ENTRYPOINT [ "npm", "start" ]
