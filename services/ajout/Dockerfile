FROM node:10

# Create app directory
WORKDIR /usr/src/app2

# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied
COPY package*.json ./

RUN npm install

# Bundle app source
COPY . .

EXPOSE 4000

CMD [ "node", "serveur2" ]
