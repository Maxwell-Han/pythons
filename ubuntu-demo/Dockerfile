FROM ubuntu:latest 

RUN apt update 
RUN apt install python3 -y 

WORKDIR /usr/app/src 

COPY  hello.py ./

CMD [ "python3", "./hello.py" ]