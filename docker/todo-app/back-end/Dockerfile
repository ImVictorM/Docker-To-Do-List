FROM node:14-alpine

EXPOSE 3001
WORKDIR /back-end
COPY . .
ADD node_modules.tar.gz .
RUN npm i
CMD [ "npm start" ]