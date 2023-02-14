FROM node:14
WORKDIR /docker
ADD ./node_modules.tar.gz .
COPY ./src .
COPY ./package-lock.json .
COPY ./package.json .
CMD [ "npm", "start" ]
EXPOSE 3001


