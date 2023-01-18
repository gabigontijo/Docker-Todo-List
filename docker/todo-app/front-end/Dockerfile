FROM alpine:3.14
EXPOSE 3000
ADD node_modules.tar.gz /docker/todo-app/back-end/node_modules.tar.gz
COPY . /front-end/
ENTRYPOINT ["npm start"]
