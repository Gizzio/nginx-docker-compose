FROM python:latest

WORKDIR /app

ADD code/requirements.txt /app/
RUN pip install -r requirements.txt

ADD uwsgi.ini /app/
ADD code /app/code
RUN pip install /app/code