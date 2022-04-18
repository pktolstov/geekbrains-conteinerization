#click==7.1.2
#Flask==1.1.2
#itsdangerous==1.1.0
#Jinja2==2.11.2
#MarkupSafe==1.1.1
#Werkzeug==1.0.1

FROM python:3.7-buster
RUN pip3 install Flask==1.1.2
RUN pip3 install click==7.1.1
RUN pip3 install itsdangerous==1.1.0
RUN pip3 install Jinja2==2.11.2
RUN pip3 install MarkupSafe==1.1.1
RUN pip3 install Werkzeug==1.0.1
RUN mkdir /opt/myapp
COPY app.py /opt/myapp/
ENTRYPOINT python3 /opt/myapp/app.py 


