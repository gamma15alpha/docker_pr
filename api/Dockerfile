FROM node:alpine

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install

COPY ./src ./src
COPY index.mjs ./

EXPOSE 5000

CMD ["npm", "start"]
