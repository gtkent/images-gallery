FROM node:latest

WORKDIR /app

EXPOSE 3000

COPY package.json package-lock.json ./

RUN npm install -g npm@8.19.3
RUN npm install --silent

COPY . ./

CMD ["npm", "start"]