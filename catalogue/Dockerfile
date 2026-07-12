FROM nodejs:20
WORKDIR /app
COPY package.json .
COPY *.js .
ENV MONGO="true" \
    MONGO_URL="mongodb://mongodb:27017/catalogue"
CMD ["node", "server.js"]