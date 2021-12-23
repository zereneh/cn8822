FROM node:16
LABEL maintainer="zereneh@ryerson.ca"

# App directory
WORKDIR /usr/src/app

#Install dependencies
COPY package*.json ./

RUN npm install 

#Bundle source code
COPY . .

#Map port 8080
EXPOSE 8080

CMD [ "node", "server.js" ]


