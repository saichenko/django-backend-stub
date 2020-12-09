FROM python:3.9-slim AS server

RUN mkdir /server
WORKDIR /server

COPY ./server/requirements.txt /server/
RUN pip install -r requirements.txt

COPY ./server /server
