FROM node:18-alpine3.17

ENV PNPM_VERSION 7.13.4

RUN npm i -g pnpm@${PNPM_VERSION}

COPY docker-entrypoint.sh /usr/local/bin

ENTRYPOINT ["docker-entrypoint.sh"]

CMD ["pnpm"]

