FROM node:25.6.0-bookworm

WORKDIR /app/customer

COPY package.json .

RUN npm install

COPY . .

EXPOSE 8001

CMD ["npm", "start"]