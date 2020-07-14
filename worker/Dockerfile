FROM node:alpine
WORKDIR "/alpine"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm", "run", "start"]
