FROM python:3.11
WORKDIR /app
COPY requirements.txt ./
RUN  pip install -r requirements.txt
COPY . .
EXPOSE 5000
ENTRYPOINT ["python", "app.py"]