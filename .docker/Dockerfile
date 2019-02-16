FROM python:3.6

ENV PYTHONUNBUFFERED 1

# Enable the below proxy config if you are using any proxies 
ENV http_proxy proxy.example.com:80
ENV https_proxy proxy.example.com:80

RUN mkdir /application
WORKDIR "/application"

ADD requirements.txt /application/
RUN pip install -r requirements.txt
