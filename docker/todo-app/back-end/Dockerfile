FROM node:14-alpine
WORKDIR /todo-app/back-end/
EXPOSE 3001
ADD ./node_modules.tar.gz ./todo-app/back-end/
COPY ./docker/todo-app/back-end ./todo-app/back-end/
ENTRYPOINT [ "npm" ]
CMD [ "start" ]
