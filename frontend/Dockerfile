FROM node:alpine

WORKDIR /fronted 

COPY package*.json .


RUN npm install

COPY . .


EXPOSE 3000

CMD ["npm", "run","dev"]