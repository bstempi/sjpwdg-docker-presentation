FROM python:3.6
MAINTAINER Brian Stempin "brian.stempin@gmail.com"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]