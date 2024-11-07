FROM node:13-alpine

WORKDIR /usr/backend

COPY . .
RUN rm -rf node_modules/ package-lock.json && \
    npm install && \
    npm install nodemon


ENTRYPOINT ["npm", "run"]

CMD ["start"]