# flask-app-docker

Aplicación Python containerizada con Docker, lista para despliegue en cualquier entorno.

## ¿Qué hace?

App web desarrollada con Flask, empaquetada en una imagen Docker. Incluye configuración para desarrollo local y base para integración en pipelines CI/CD.

## Stack

`Python` · `Flask` · `Docker` · `Shell`

## Uso

```bash
git clone https://github.com/lucaseveron/flask-app-docker
cd flask-app-docker

# Build de la imagen
docker build -t flask-app .

# Correr el contenedor
docker run -p 5000:5000 flask-app
```

La app queda disponible en `http://localhost:5000`.

## Requisitos

- Docker >= 20.x

## Estructura

```
flask-app-docker/
├── app/          # Código fuente de la aplicación
├── Dockerfile    # Definición de la imagen
└── README.md
```
