FROM node:alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY ./src ./src
COPY index.html ./
COPY vite.config.js ./

EXPOSE 8954

CMD ["npm", "run", "dev"]
