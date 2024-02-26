# Verwende das offizielle nginx-Basisimage
FROM nginx

# Setze das Arbeitsverzeichnis im Container auf das Verzeichnis, in dem die nginx-Dateien normalerweise gehostet werden
WORKDIR /usr/share/nginx/html

# Kopiere die helloworld.html Datei aus dem Build-Kontext in das Arbeitsverzeichnis des Containers
COPY helloworld.html .

# Öffne den Port 80 im Container, um eingehende Verbindungen zu akzeptieren
EXPOSE 80
