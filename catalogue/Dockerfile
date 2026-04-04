FROM node:18-bullseye 
# this creates and moves to this directory
WORKDIR /app
COPY package.json .
RUN npm install
COPY *.js .
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "server.js"]