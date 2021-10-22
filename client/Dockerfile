FROM node:alpine
WORKDIR /app

COPY . ./
RUN npm install 
RUN npm config set unsafe - perm true
RUN mkdir -p node_modules/.cache && chmod -R 777 node_modules/.cache


CMD ["npm", "start"]
