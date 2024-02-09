
FROM python:3.11

WORKDIR /app
COPY requirements.txt .

RUN pip install -r requirements.txt && rm requirements.txt

COPY main.py .

EXPOSE 8000


ENTRYPOINT ["python", "main.py"]