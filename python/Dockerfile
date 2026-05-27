FROM python:3.12-slim

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY script.py . 
#siempre va de ultimo

CMD ["python", "script.py"]