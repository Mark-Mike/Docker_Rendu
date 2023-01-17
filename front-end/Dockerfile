# obtain nodejs image
FROM node:18.12.1-alpine

# install angular dependencies
RUN npm install -g @angular/cli

# specify the workspace for the application in order to run it
# WORKDIR /front/app1
WORKDIR /front/material-dashboard-angular2

# expose the angular ports
EXPOSE 4200 49153

# execute command start
RUN npm install --save-dev @angular-devkit/build-angular
CMD npm start
