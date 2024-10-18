FROM docker.io/node:18-alpine

WORKDIR /usr/app

COPY ./package.json ./

#Install dependanices
RUN npm install

#Copy the rest of files
COPY ./ ./
#Startup Command

CMD ["npm", "start"]