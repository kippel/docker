FROM python:3.10-alpine

ENV PYTHONUNBUFFERED 1

COPY ./requirements.txt /requirements.txt
COPY ./code /code

WORKDIR /code
EXPOSE 8000

RUN python -m venv /py && \
    /py/bin/pip install --upgrade pip && \
    /py/bin/pip install -r /requirements.txt && \
    adduser --disabled-password --no-create-home web

ENV PATH="/py/bin:$PATH"

USER web
