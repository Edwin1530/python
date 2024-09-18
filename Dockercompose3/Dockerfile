# Utiliser une image Python officielle
FROM python:3.9-slim

# Définir le répertoire de travail dans le conteneur
WORKDIR /app

# Copier le fichier requirements.txt dans le répertoire de travail
COPY requirements.txt .

# Installer les dépendances
#RUN pip install --no-cache-dir -r requirements.txt

# Copier le reste des fichiers de l'application dans le conteneur
COPY main.py .

# Définir la commande par défaut qui sera exécutée lorsque le conteneur démarre
CMD ["python", "main.py"]
