FROM node:8
RUN mkdir -p /usr/src/app
COPY ./server/* /usr/src/app/
COPY ./config/* /usr/src/config/
EXPOSE 3000
RUN npm install socket.io
CMD [ "node", "/usr/src/app/server" ]