FROM node:20
WORKDIR /app
COPY *.json .
COPY *.js .
RUN npm install
CMD ["node", "server.js"]