FROM node:latest

# Install a specific version of npm
RUN npm install -g npm@6.14.4

WORKDIR app/
COPY index.js .
COPY package.json .
RUN npm install
CMD ["node", "index.js"]

