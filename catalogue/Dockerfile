FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install    # installing dependencies
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node","server.js"]
