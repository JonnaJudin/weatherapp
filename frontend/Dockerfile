FROM node:10 as react-build

RUN mkdir -p /app/frontend

WORKDIR /app/frontend

COPY package* /app/frontend/

RUN npm install

COPY . /app/frontend

CMD ["npm", "start"]

