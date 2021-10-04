FROM python:2.7

COPY requirements.txt /usr/app/requirements.txt
COPY app.py /usr/app/app.py

RUN pip install -r /usr/app/requirements.txt

EXPOSE 5000
ENTRYPOINT ["python", "/usr/app/app.py"]
