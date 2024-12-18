# APIBicis
Proxecto de fin de avaliación de Sistemas de Big Data. Obteremos datos en tempo real da API Citybikes para saber o estado das estacións de aluguer de bicicletas e almacearemolos nunha base de datos de MongoDB.

# Funcións principais do proxecto:
- Conectaremonos a API de cada 5 minutos.
- Almacearemos os datos obtidos en MongoDB.
- Usaremos Docker para o uso de Mongo.

# Instalación de MongoDB con Docker:
Unha forma rápida e sinxela de facelo sería a través da terminal co seguinte comando:
- docker run --name mongo -d -p 27017:27017 mongo

Outra opción é usar docker-compose, tamén incluido.

# Acceso a base de datos:
Na consola:
- docker exec -it mongo bash
- mongosh

En MongoDB:
- use citybikes_db
- db.stations.find()

