FROM python:3.8-slim

WORKDIR /app

COPY requirements.txt ./

RUN pip install -r requirements.txt

COPY . .

EXPOSE 5000

# Posiblemente haya que añadir , "main.py" al final de la siguiente línea
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]
