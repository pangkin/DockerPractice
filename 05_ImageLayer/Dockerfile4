FROM ubuntu

RUN apt update && apt install -y -q nginx

COPY index.html /usr/share/nginx/html

CMD ["nginx", "-g", "daemon off;"]
