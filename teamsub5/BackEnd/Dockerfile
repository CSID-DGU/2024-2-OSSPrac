# Dockerfile at BackEnd

# 이미지명
FROM python:3

# python 컨테이너에서 사용되는 경로
# 실제로 본 이미지를 실행해보면 /usr/src/app 경로에서 python이 실행되는 것을 확인 가능함
WORKDIR /usr/src/app

# 현재 local 경로에 있는 디렉토리(prac5)를 컨테이너 내부로 copy함
COPY . .

# python ./main.py가 실행됨. 이때, main.py는 본인의 python 파일 이름으로 변경 가능
CMD [ "python3", "main.py" ]
