FROM node
COPY package.json .
RUN npm install
COPY app.js .
COPY index.html .
COPY keycloak.json .

EXPOSE 8000
CMD [ "npm", "start" ]