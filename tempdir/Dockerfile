FROM python
RUN pip install flask
COPY  ./static /home/myapp/static/
COPY  ./templates /home/myapp/templates/
COPY  design_app2.py /home/myapp/
EXPOSE 5050
CMD python3 /home/myapp/design_app2.py
