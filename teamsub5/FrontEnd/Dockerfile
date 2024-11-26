FROM python:3.9

WORKDIR /app

COPY . /app

RUN pip install --no-cache-dir uwsgi flask

EXPOSE 80

CMD ["uwsgi", "--ini", "uwsgi.ini"]
