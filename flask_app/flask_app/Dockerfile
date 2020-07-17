FROM python:3.5-slim
WORKDIR /app
ADD . /app
RUN pip3 install --trusted-host pypi.python.org -r requirements.txt
EXPOSE 5000
ENV NAME OpentoAll
CMD ["python","app.py"]
