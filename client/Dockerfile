FROM node

WORKDIR /client

COPY package*.json /client/

RUN npm install

COPY . /client/

EXPOSE 3000
CMD [ "npm", "start"]

#FROM node:alpine
#WORKDIR /app
#COPY package.json .
#RUN yarn install
#COPY . .
#CMD ["yarn", "start"]