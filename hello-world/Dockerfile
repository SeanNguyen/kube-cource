FROM python:2.7

ENV FLASK_APP app.py

COPY . /app

WORKDIR /app

RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "-m", "app"]