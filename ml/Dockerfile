FROM python:3.10-slim

WORKDIR /app

RUN apt-get update && apt-get install -y ca-certificates

COPY . .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "api.py"]