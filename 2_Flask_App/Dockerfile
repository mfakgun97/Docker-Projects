FROM python:3.8-slim

WORKDIR /app

COPY . .

#install the dependencies from the requirements file
RUN pip install --no-cache-dir -r requirements.txt

CMD ["python","app.py"]
