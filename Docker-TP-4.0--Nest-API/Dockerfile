FROM node:hydrogen-slim

WORKDIR /api/

COPY . . 

RUN npm i

EXPOSE 3000

CMD ["/bin/bash", "-c", "npm run start"]