FROM node:20-alpine
WORKDIR /src/app
COPY package*.json ./
RUN npm install
COPY ./src .
EXPOSE 4000
CMD ["npm","run","dev"]
