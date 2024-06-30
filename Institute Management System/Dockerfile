
FROM node:20-buster-slim


WORKDIR /app


COPY package.json package-lock.json ./


RUN npm install --silent


COPY . .


CMD ["npm", "start"]
