FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  login-app.py /home/myapp/
EXPOSE 5050
CMD python /home/myapp/login-app.py
