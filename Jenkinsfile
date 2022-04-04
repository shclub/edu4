FROM python:3.8-slim

# set the working directory in the container to /app
WORKDIR /app

# add the current directory to the container as /app
ADD . /app

RUN pip install -r requirements.txt

# unblock port 80 for the Flask app to run on
EXPOSE 40006

# execute the Flask app
CMD ["python", "app.py"]
