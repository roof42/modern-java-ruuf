podman run -p 6379:6379 --name some-redis -d redis
podman run -d --name vsftpd -p 2121:21 -p 21100-21110:21100-21110 -e FTP_USER=one -e FTP_PASS=1234 fauria/vsftpd