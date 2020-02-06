FROM node:12
ENV TZ=Asia/Shanghai
RUN mkdir -p /usr/src && npm config set unsafe-perm true && npm i egg-init -g
WORKDIR /usr/src
EXPOSE 7001
ENV PATH=/usr/src/node_modules/.bin:$PATH
CMD npm start
