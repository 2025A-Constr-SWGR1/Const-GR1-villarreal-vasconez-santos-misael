
FROM node:22.14.0-bullseye

WORKDIR /app

COPY package.json package-lock.json ./

RUN npm install
 
COPY dist/ ./dist

EXPOSE 3000

CMD ["node", "dist/main.js"]