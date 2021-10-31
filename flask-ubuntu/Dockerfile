FROM ubuntu:latest

RUN apt-get update -y
RUN apt-get install -y python3-pip python-dev build-essential

WORKDIR /app

COPY requirements.txt /app
COPY instruction.md /app

RUN pip install -r requirements.txt

ENTRYPOINT ["python"]
CMD ["app.py"]