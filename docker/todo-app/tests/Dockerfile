FROM node:14-alpine

WORKDIR /tests-app

COPY . .

RUN npm install

ENV FRONT_HOST=todofrontend

ENV FRONT_PORT=3000

CMD ["npm", "test"]
