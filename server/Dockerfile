FROM node:alpine

WORKDIR '/app'
COPY ./package.json ./
RUN npm install --verbose


#RUN npm install --verbose

COPY . /app

CMD ["npm","run","start"] 