FROM node:alpine
WORKDIR /app
COPY ./package.json .
RUN npm install
Run npm install -g npm@7.22
RUN npm config set unsafe-perm true
COPY . .
CMD ["npm","run", "start"]
