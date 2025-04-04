FROM python:3.11-alpine
RUN apk add --no-cache git
WORKDIR /app
RUN git clone https://github.com/RobinSchfr/Lightning-control-for-Nanoleaf.git .
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 8080
CMD ["python3", "src/main.py"]