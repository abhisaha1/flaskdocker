FROM python:3.6-alpine
# RUN apt-get install -y build-essential python3.6  python3-pip
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
EXPOSE 5000
CMD ["app.py"]