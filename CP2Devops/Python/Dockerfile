FROM python:3.9-slim

WORKDIR /app

ARG APP_NAME
ENV APP_NAME=$APP_NAME

COPY appRM97798.py /app

RUN chmod +x /app/appRM97798.py 
CMD ["python", "/app/appRM97798.py"]