FROM node:boron
WORKDIR /app
COPY src/. /app/
RUN npm install
EXPOSE 3001
CMD [ "node", "/app/index.js" ]