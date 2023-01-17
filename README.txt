

# This is a full satck application that i started from scratch, it is not functional but all the functionalities runs and ready to be used



# Before all in docker-compose.yml, the path in the volumes of angular should be modified 
# to adapt it according to the file system that is used. More explanation is found in the comments

# The first step is to execute the command:
docker-compose up -d --build  # in detached mode, and build, to build the images

# notice: the front application take a long time to build..

# next we will have our back and front end running in the urls:
- front : localhost:4200
- back : localhost:5000

