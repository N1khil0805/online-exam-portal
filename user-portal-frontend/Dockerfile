FROM node:13-alpine

WORKDIR /usr/user-portal-frontend

COPY . .

RUN rm -rf node_modules/ package-lock.json && \
           npm install && \
           npm run build

ENTRYPOINT ["npm"]
CMD ["start"]