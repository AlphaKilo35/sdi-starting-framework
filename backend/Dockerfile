FROM node:20-alpine

RUN mkdir -p /backend

WORKDIR /backend

COPY . /backend

RUN npm install
  #assuming node.js / react

EXPOSE 3000
  #Default express server port

CMD ["npm", "start"]
  #Break up command in package.json
  # [ "npm", "run", "dev"] / ["npm", "start"] / ["npm", "run"]