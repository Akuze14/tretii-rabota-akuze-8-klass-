FROM python:3.9-slim

WORKDIR /app

COPY cleanup_script.py .

RUN pip install --no-cache-dir psutil

ENTRYPOINT ["python", "cleanup_script.py"]


BY AKUZE 8 klass mechta DEV OPS eto doker ya dumayu vy znayete chto eto takoe