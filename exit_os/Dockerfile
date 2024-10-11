# Imatge base d'Ubuntu 20.04 per l'arquitectura aarch64
FROM ghcr.io/home-assistant/aarch64-base-ubuntu:20.04

# Afegim el camí de bashio per utilitzar funcions
ENV PATH="${PATH}:/usr/lib/bashio"

# Actualitzem i instal·lem python, pip, i altres eines necessàries
RUN apt update && apt install -y dos2unix python3 python3-pip \
    && pip install --upgrade pip \
    && pip install scikit-learn psutil func_timeout requests numpy pandas pyswarms tomli

# Copiem el sistema de fitxers arrel
COPY rootfs /

# Copiem el fitxer de configuració de l'add-on
COPY config.yaml config.yaml

# Instal·lem les biblioteques de Python necessàries
RUN pip install holidays 

# Convertim fitxers Python específics al format LF
RUN dos2unix ./etc/abstraction/*.py

# TODO: Prova de convertir tots els fitxers al format LF perquè GitHub els converteix a CRLF
# RUN find /rootfs -type f -exec dos2unix {} \;
