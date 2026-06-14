from python:3.10-slim
workdir /app
copy requirements.txt
run pip install --no-cache-dir -r requirements.txt

copy app ./app
expose 5000
cmd ["python","app.py/main.py"]


