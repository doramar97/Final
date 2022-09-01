FROM python:slim

EXPOSE 8081

RUN pip install flask
 
WORKDIR /app

ADD web.py .

CMD ["python","web.py"]