FROM node:14.14.0-alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY ./ ./
# give the production envirment command
# check if the you have "start" script defined in package.json.
CMD ["npm","run","start"]