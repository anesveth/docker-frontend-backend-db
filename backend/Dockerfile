#base image
FROM node:10-alpine
WORKDIR /backend
COPY . .
RUN npm install
EXPOSE 3001
CMD [ "server.js" ]
ENTRYPOINT [ "node" ]
