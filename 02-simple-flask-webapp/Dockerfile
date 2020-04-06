FROM python:alpine

RUN pip install flask

WORKDIR /opt

COPY ./app.py ./

EXPOSE 5000

CMD python ./app.py
