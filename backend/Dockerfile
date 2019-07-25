FROM node:10

RUN mkdir -p /app/backend
WORKDIR /app/backend

COPY package* /app/backend/

RUN npm install

COPY . /app/backend

CMD ["npm", "start"]

