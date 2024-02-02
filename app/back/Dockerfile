FROM python:3.10


COPY . /app/back
WORKDIR /app/back
RUN pip install -r requirements.txt
EXPOSE 5000


CMD ["python3", "app.py"]

python3 -m flask run --host=0.0.0.0
