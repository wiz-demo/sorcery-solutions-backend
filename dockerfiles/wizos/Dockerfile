FROM registry.os.test.wiz.io/python:3.12

WORKDIR /app

COPY ../../app /app/
RUN pip install -r /app/requirements.txt --upgrade --no-cache-dir

ENTRYPOINT ["fastapi", "run", "main.py", "--port", "8000"]