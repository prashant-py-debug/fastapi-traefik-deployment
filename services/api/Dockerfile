FROM python:3.9.7-slim

WORKDIR ./app

ADD ./requirements.txt .

RUN pip install -r requirements.txt

EXPOSE 8000

ADD . /app

CMD uvicorn main:app --host 0.0.0.0