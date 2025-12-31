# create the base image.
FROM node:18.9.1

# create the app diretory 
WORKDIR /app

# copy the package of this project.
COPY package.json .

# enter the run command
RUN npm install

# copy the code of the current directory 
COPY . .

# Expose the port number.
EXPOSE 5173

# command for run the app.
CMD [ "npm","run","dev" ]
