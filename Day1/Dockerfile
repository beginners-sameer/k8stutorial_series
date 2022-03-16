FROM python:2.7-onbuild
COPY requirements.txt /tmp
RUN pip install -r /tmp/requirements.txt
EXPOSE 8080
CMD ["python", "app.py"]
