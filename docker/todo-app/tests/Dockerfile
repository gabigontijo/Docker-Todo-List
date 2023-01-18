FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz /docker/todo-app/tests/node_modules.tar.gz
COPY . /tests/
ENTRYPOINT ["npm start"]
