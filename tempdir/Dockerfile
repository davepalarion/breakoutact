FROM python
RUN pip install flask
RUN pip install ipapi
COPY  ./templates /home/myapp/templates/
COPY  ipflask.py /home/myapp/
EXPOSE 8080
CMD python3 /home/myapp/ipflask.py
