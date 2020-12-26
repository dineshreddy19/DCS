#!/bin/bash

FROM python:3.7

MAINTAINER Dinesh Reddy "dineshreddy.y19@gmail.com"

COPY ./requirements.txt /app/requirements.txt

WORKDIR /app

RUN pip install --upgrade pip
RUN pip install -r requirements.txt

COPY . /app

ENTRYPOINT [ "python" ]

CMD [ "app.py" ]
