FROM node:14 AS todobackend
EXPOSE 3001
WORKDIR /todo-app
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]