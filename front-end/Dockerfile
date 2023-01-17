# obtain nodejs image
FROM node:14-alpine 

# install angular dependencies
RUN npm install -g @angular/cli

USER node

# main repository
WORKDIR /

# copy our angular repository to a new folder
COPY ./material-dashboard-angular2-master ./front

# expose the angular ports
EXPOSE 4200 49153

# execute command start
CMD npm start