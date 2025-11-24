# Albuaves
## Tecnologias usadas

* java
* sqlitebrowser
* php-sqlite3

## Como poner el servidor en marcha

Primero de todo vamos a instalar los programas necesarios y actualizar todo:

```bash
sudo apt update
sudo apt install sqlitebrowser php-sqlite3
sudo apt install default-jdk
sudo apt install php
```
Una vez instalados hay que poner en marcha el servidor:

```bash
./run-api-server.sh
```

Despues preparamos los archivos java:

```bash
javac -cp json-20250517.jar SearchBirdsAPI.java
javac albuaves_api_rest.java
```

Por ultimo accedemos a la direccion del servidor, en mi caso (http://127.0.0.1:9191)  
  
Y ya nos mostraria las aves con el servidor en linea.
