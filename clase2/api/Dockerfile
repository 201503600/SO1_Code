FROM node:alpine3.11
WORKDIR /API1
COPY package.json .
COPY package-lock.json .
COPY . .
RUN npm install
EXPOSE 3000 
CMD ["npm","start"]