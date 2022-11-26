FROM node:18.12.1
WORKDIR /opt/app
ADD . .
RUN npm install -g npm@9.1.2
RUN npm run build api
CMD ["node",".dist/apps/api/main.js"]
