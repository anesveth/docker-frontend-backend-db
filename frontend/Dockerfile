#base image
FROM node:14-alpine
WORKDIR /frontend
COPY . . 
RUN npm install
EXPOSE 3000
CMD [ "start" ]
ENTRYPOINT [ "npm" ]