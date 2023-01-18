FROM alpine:3.14
EXPOSE 3001
ADD node_modules.tar.gz /docker/todo-app/back-end/node_modules.tar.gz
COPY . /back-end/
ENTRYPOINT ["npm start"]