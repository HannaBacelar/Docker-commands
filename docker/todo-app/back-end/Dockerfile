FROM node:14-alpine AS todobackend

WORKDIR /

EXPOSE 3001

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm","start"]
