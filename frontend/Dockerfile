FROM node:latest 

WORKDIR /app


COPY package*.json .

RUN npm install --upgrade npm

COPY . .
COPY .env.local .env.local 

EXPOSE 5173
CMD ["npm","run","dev","--","--host"]
