FROM node:14-alpine AS todofrontend

WORKDIR /

EXPOSE 3005

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm","start"]

