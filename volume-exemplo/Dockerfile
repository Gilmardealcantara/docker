FROM node:latest
MAINTAINER Gilmar Alcantara
COPY . /var/www
ENV NODE_ENV="Production"
ENV PORT=3000
WORKDIR /var/www
RUN npm install
ENTRYPOINT ["npm", "start"]
EXPOSE $PORT
