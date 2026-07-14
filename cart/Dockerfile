FROM node:20
WORKDIR /app
COPY .json* /app
COPY .js* /app
RUN npm install
CMD ["node", "server.js"]