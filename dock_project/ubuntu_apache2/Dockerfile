FROM ubuntu:focal

ENV DEBIAN_FRONTEND=noninterective
# 아파치 설치
RUN apt-get update && apt-get install -y apache2 git
RUN git clone https://github.com/malsoonkang/test_page.git
RUN cp -r test_page/* /var/www/html/


# 포트 열기
EXPOSE 80

# 아파치 서버 실행
CMD ["apachectl", "-D", "FOREGROUND"]

