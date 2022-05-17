FROM mjgargani/puppeteer:trybe1.0 AS todotests

WORKDIR /

EXPOSE 3002

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm","test"]


