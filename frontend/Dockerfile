FROM node:19-alpine

WORKDIR /app
COPY package*.json yarn.lock ./
RUN yarn install

COPY . .
EXPOSE 8080
CMD ["yarn", "serve"]
