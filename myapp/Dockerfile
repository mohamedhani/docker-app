From python:alpine
COPY basic-flask-app /app
WORKDIR /app
RUN ["pip","install","-r","requirements.txt"]
ENTRYPOINT ["python","routes.py"]
