FROM python:3.12-alpine

WORKDIR /app

COPY script.py .

RUN adduser -D scriptuser
USER scriptuser

EXPOSE 8080

CMD ["python", "script.py"]