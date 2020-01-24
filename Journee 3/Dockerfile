FROM ubuntu
RUN apt update
RUN apt -y install sudo
RUN sudo apt -y install python3
RUN apt-get install python3 python3-pip git virtualenv -y
COPY requirements.txt .
RUN pip3 install -r requirements.txt
