# Dockerfile.node
FROM node:14-alpine

WORKDIR /app

COPY ["package.json", "package-lock.json", "./"]
RUN npm install --quiet
COPY . .

EXPOSE 3000

CMD ["npm", "start"]