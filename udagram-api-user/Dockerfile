<<<<<<< HEAD
FROM node:12
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies
# A wildcard is used to ensure both package.json AND package-lock.json are copied where available (npm@5+)
=======
FROM node:13
# Create app directory
WORKDIR /usr/src/app
# Install app dependencies

>>>>>>> 90702b3a3c6da43865960255e40048e3b8dd93a6
COPY package*.json ./
RUN npm ci 
# Bundle app source
COPY . .
EXPOSE 8080
CMD [ "npm", "run", "prod" ]
