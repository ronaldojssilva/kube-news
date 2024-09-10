FROM node:22-alpine3.19
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]

# # docker build -t ronaldojssilva/kube-news:v1 -f src/Dockerfile src/
# # docker tag ronaldojssilva/kube-news:v1 ronaldojssilva/kube-news:latest