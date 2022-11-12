FROM node:14-alpine

EXPOSE 3001

COPY . .
ADD node_modules.tar.gz .
RUN npm i
CMD [ "npm start" ]