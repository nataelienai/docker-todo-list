FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
ADD node_modules.tar.gz ./
COPY package*.json ./
RUN npm install
COPY . .
ENTRYPOINT [ "npm", "test" ]
