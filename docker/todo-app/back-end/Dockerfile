FROM node:14-alpine
WORKDIR /app
COPY package*.json ./
ADD node_modules.tar.gz node_modules/
RUN npm install
COPY src/ src/
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]
