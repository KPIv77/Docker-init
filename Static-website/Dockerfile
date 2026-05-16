FROM nginx:alpine

# ลบ default nginx page
RUN rm -rf /usr/share/nginx/html/*

# copy static files เข้าไป
COPY . /usr/share/nginx/html

EXPOSE 80