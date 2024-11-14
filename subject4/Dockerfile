# 베이스 이미지로 Python 3.9 사용
FROM python:3.13

# 작업 디렉토리를 /app으로 설정
WORKDIR /app

# 현재 디렉토리의 app 폴더를 컨테이너의 /app으로 복사
COPY ./app /app

# 필요한 패키지 설치 (Flask와 uWSGI)
RUN pip install flask uwsgi

# uWSGI를 사용하여 애플리케이션 실행
CMD ["uwsgi", "--ini", "uwsgi.ini"]
