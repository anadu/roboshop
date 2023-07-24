FROM node:14

EXPOSE 8080

WORKDIR /opt/kishore

COPY package.json /opt/kishore/

# npm install get the dependencies of node js project
RUN npm install 

COPY server.js /opt/kishore/

ENTRYPOINT ["node", "server.js"]

