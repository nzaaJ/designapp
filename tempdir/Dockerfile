FROM python
RUN pip install flask
COPY  ./templates /home/myapp/templates/
COPY  ./static /home/myapp/static/
COPY  login.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/login.py
