FROM python:3.13
WORKDIR /app
COPY ./app /app
RUN pip install flask uwsgi
CMD ["uwsgi", "--ini", "uwsgi.ini"]
