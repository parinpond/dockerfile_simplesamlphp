
openssl req -x509 -nodes -days 365 -newkey rsa:4096 -subj "/C=TH/ST=Bangkok/L=sapanmai/O=bali/CN=bali" -keyout ./ssl/ssl.key -out ./ssl/ssl.crt