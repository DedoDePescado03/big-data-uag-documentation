Imagen: Instrucciones para ejecutar contenedores
Contenedor
Dockerfile: Archivo de texto, con instrucciones de como construir contenedores

Volumen:
Red: Para que los contenedores se comuniquen por la red de docker

Registro: Biblioteca de imágenes 


Comandos

```console
mkdir flask-demo -Crear aplicaciones
docker build -t my-flask-image .
Docker run -d -p 5050:5050 --name flask-app my-flask-image
```

-d: Segundo plano
-p: puerto

http://localhost:5050

```console
Docker ps
Docker exec -it flask-app bash
```

Extract Transform Load (ETL)
Recolectar -> Construir -> Almacenar -> Procesar