FROM python:3.6.7

ENV PYTHONBUFFERED 1

RUN mkdir /code
WORKDIR /code

ADD requirements.txt /code/
RUN pip3 install -r /code/requirements.txt
ADD . /code/