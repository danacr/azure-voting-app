FROM    danacr/uwsgi-nginx-flask-arm64

RUN     apt-get update && \
        apt-get install default-libmysqlclient-dev -y && \
        pip install flask-mysql
 
ADD     /azure-vote /app