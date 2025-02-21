FROM node:18.18.1

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

EXPOSE 5000


# CMD ["npm","run","build"]
# CMD ["npm", "start"]
CMD ["npm", "run",  "dev", "--","-p", "5000"]
