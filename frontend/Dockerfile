FROM node:20-slim

ENV ROLLUP_SKIP_NODEJS_NATIVE=true

WORKDIR /frontend

COPY package*.json ./

RUN npm ci

COPY . .

EXPOSE 8080
CMD ["npm", "run", "dev"]
