FROM python:3.7

RUN apt-get update && apt-get install apt-file -y && apt-file update && apt-get install tree -y

RUN pip3 install virtualenv

RUN python3 -m virtualenv /opt/venv

RUN chmod -R 777 /opt/venv