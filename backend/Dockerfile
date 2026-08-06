FROM node:18-alpine

WORKDIR /app

# Dependency files copy & install
COPY package*.json ./
RUN npm install

# Rest of the code copy
COPY . .

EXPOSE 5000

# Direct src/server.js point kore dewa holo
CMD ["node", "src/server.js"]
