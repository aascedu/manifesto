FROM nginx:alpine

RUN mkdir -p /etc/nginx/ssl && \
    apk add --no-cache openssl && \
    openssl req -x509 -nodes -out /etc/nginx/ssl/manifesto.crt -keyout /etc/nginx/ssl/manifesto.key -subj "/C=FR/CN=arthurascedu"