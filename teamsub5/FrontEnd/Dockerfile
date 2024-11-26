FROM python:3.9

# 작업 디렉토리 설정
WORKDIR /app

# 애플리케이션 소스 코드를 모두 복사
COPY . /app

# 필요한 패키지 직접 설치
RUN pip install --no-cache-dir uwsgi flask

# 포트 노출 (예: 80번 포트)
EXPOSE 80

# 컨테이너 실행 시 실행할 명령어
CMD ["uwsgi", "--ini", "uwsgi.ini"]
