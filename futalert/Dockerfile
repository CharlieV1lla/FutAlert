FROM python:3
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1
RUN mkdir /futalert
WORKDIR /futalert
COPY requirements.txt /futalert/
RUN pip install -r requirements.txt
COPY . /futalert/
