FROM node:14 AS todofrontend
EXPOSE 3000
WORKDIR /todo-app-frontend
ADD ./node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm", "start"]
