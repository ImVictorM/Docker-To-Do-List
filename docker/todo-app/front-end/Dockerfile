FROM node:14-alpine

EXPOSE 3000
ENV REACT_APP_API_HOST=todobackend
ENV REACT_APP_API_PORT=3001
WORKDIR /front-end
COPY . .
ADD node_modules.tar.gz .
RUN npm i
ENTRYPOINT [ "npm", "start" ]
