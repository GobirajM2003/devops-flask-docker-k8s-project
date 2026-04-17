FROM python:3.10

WORKDIR /app

COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

COPY Layer1_backend.py .

EXPOSE 9000

CMD ["python", "Layer1_backend.py"]