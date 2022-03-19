FROM node:16.4.1

# set working directory
WORKDIR /app

# install app dependencies
COPY package*.json ./


RUN npm install 


# add app
COPY . .


EXPOSE 80
# start app
CMD ["npm", "start"]
