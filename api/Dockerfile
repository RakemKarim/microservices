# Dockerfile pour l'API
FROM python:3.11-slim

WORKDIR /app

# Installer Flask
RUN pip install flask

# Copier le code
COPY app.py .

# Exposer le port de l'API
EXPOSE 5000

# Lancer l'application
CMD ["python", "app.py"]
