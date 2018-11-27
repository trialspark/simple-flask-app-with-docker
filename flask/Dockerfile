FROM python:3.6

ADD ./requirements.txt .
RUN pip install -r requirements.txt --src ./pip-src

VOLUME /app/pip-src

ENV PYTHONPATH /app
