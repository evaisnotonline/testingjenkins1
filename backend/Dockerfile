FROM python:3.7

WORKDIR /app

RUN pip install -r requirements.txt

COPY . .

EXPOSE 5001

ENTRYPOINT ["python", "app.py"] 
