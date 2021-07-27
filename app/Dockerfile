# syntax=docker/dockerfile:1
 FROM node:12-alpine
 RUN apk add --no-cache python g++ make
 WORKDIR /app
 COPY . .
 RUN yarn install --production
 CMD ["node", "src/index.js"]

 ## based on a Node image
 ## first installs dependencies via apk (Python, G++ compiler, and Make)
 