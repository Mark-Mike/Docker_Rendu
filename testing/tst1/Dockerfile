
FROM ubuntu

RUN apt-get update
RUN apt-get install -y gedit

COPY workdir/ /intern_workspace/workdir/

#CMD ["bash"]

EXPOSE 8291

WORKDIR /intern_workspace/workdir/

CMD gedit Hi.txt
