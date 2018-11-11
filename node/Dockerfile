FROM node:8

WORKDIR /usr/src/app

COPY $PROJECT_DIR/package*.json ./

# Configure this to ignore dev dependencies in prod with --only=production
RUN  npm install

COPY $PROJECT_DIR .

CMD [ "npm", "start" ]
