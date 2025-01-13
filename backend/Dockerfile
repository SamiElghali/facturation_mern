FROM node:20.12.2-alpine
WORKDIR /app
COPY ./package*.json ./
RUN npm install --force
COPY . .
EXPOSE 3000
CMD ["node", "index.js"]
