FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN apt-get update -y
RUN pip install redis
ADD /azure-vote /app
