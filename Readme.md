# Introducción a las bases de datos documentales

Proyecto de ejemplo para aprender cómo trabajar con BBDD NoSQL.

Índice de contenido:

* [Bases de datos NoSQL](00-BasesDatosNoSQL.md)
* [Introducción a MongoDB](01-MongoIntro.md)
* [Introducción a Flask](02-IntroFlask.md)


Si estás clonando este proyecto recuerda crear el entorno virtual, activarlo e installar las bibliotecas necesarias. Ejemplo para Linux:

```sh
python3.10 -m venv venv
. ./venv/bin/activate
pip install -r requirements.txt
```

Recuerda que en cualquier momento puedes desactivar el **Virtual Environment** con `deactivate`.


encender
    instalar python 3.10
    en docker -> 8081
        mongosh -u root -p
        use deporte
        meter base de datos

    en backedn -> 8080
        python3.10 -m venv venv  
        .\venv\Scripts\activate
        pip install -r .\requirements.txt 
        flask run --port 8080