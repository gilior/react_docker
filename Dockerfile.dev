from node:alpine
workdir '/app'
copy package.json .
RUN npm install
COPY . .
CMD ["npm", "run","start"]