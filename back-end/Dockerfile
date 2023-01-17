FROM python:3.8-slim-buster 
# obtain python image


# create repo named requirements
WORKDIR /requirements

# copy the file inside the new repo
COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

# now back to main directory
WORKDIR /

# create new repo and copy whats inside our flask code to it
COPY ./flask ./back

WORKDIR /back

# CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0"]
CMD python3 -m flask run --host=0.0.0.0
