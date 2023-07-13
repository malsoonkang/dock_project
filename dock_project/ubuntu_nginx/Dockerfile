FROM ubuntu:focal

ENV DEBIAN_FRONTEND=noninterective

# Nginx 설치
RUN apt-get update && apt-get install -y nginx

# 포트 열기
EXPOSE 80

# Nginx 서버 실행
CMD ["nginx", "-g", "daemon off;"]

