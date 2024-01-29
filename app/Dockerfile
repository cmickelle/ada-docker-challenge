#python image
FROM python:3.8-slim

#working directory
WORKDIR /app

#requirents and dependecies 
COPY ./requirements.txt /app/requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

#source code
COPY . /app

#commant to start the app
CMD ["python", "main.py"]