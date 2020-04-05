FROM node:10.15.0

ENV REFRESHED_AT 2020-04-04

WORKDIR /ui

COPY ./package*.json ./

RUN npm install
RUN npm install -g @vue/cli@4.2.3

COPY . .

EXPOSE 8080

CMD ["npm", "run", "serve"]