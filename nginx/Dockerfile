FROM nginx:1.29.7-alpine
# 설정 파일 복사
COPY default.conf /etc/nginx/conf.d/default.conf

# HTML 파일들 복사 (경로 수정: ./html/ 폴더 참조)
COPY ./html/index.html /usr/share/nginx/html/index.html
COPY ./html/company.html /usr/share/nginx/html/company.html

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]