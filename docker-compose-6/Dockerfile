FROM python:3.5.2-alpine

COPY ./requirements.txt /requirements.txt
COPY ./app.py /app.py

RUN pip install -r /requirements.txt

CMD [ "python", "/app.py" ]