FROM node:20-bullseye

WORKDIR /app

COPY . /app/

RUN npm install

ENV MONGO_USER=admin
ENV MONGO_PWD=S3cret
ENV MONGO_URL=mongodb

EXPOSE 3000

CMD ["node", "index.js"]
