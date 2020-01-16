FROM python:3

RUN pip install flask

RUN mkdir -p /corp/app
WORKDIR /corp/app
COPY main.py .
ENV FLASK_APP=/corp/app/main.py

ENV APP_NAME=CloudAcademy.DevOps
ENV APP_VERSION=v1.0.0

CMD ["flask", "run", "--host=127.0.0.1"]