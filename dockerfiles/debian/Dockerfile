FROM python:3.12-slim

WORKDIR /app

COPY ../../app /app/
RUN pip install -r /app/requirements.txt --upgrade --no-cache-dir

ENTRYPOINT ["fastapi", "run", "main.py", "--port", "8000"]
