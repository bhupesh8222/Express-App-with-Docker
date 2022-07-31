#parent image
FROM node:18-alpine3.15


WORKDIR /app

#copy from source to dest
COPY . .  

RUN npm install

EXPOSE 4000

CMD ["node" "app.js"]

