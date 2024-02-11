
# FastAPI Basic Example

Este repositorio contiene un ejemplo básico de una aplicación creada con FastAPI. FastAPI es un moderno framework web de alta performance, fácil de aprender, de construir y de desplegar, basado en estándares Python 3.7+ como type hints.

## Instalación

Asegúrate de tener Python 3.7 o superior instalado en tu sistema. Para instalar FastAPI y Uvicorn (un servidor ASGI ligero), ejecuta:

```
pip install fastapi uvicorn
```
Una vez instaladas las dependencias, puedes iniciar la aplicación ejecutando:
```
uvicorn main:app --reload
```
Esto iniciará el servidor de desarrollo en http://127.0.0.1:8000. La opción --reload hace que el servidor se reinicie tras cambios en el código.

## Cómo probar la aplicación

Para probar la aplicación, puedes utilizar tu navegador o una herramienta como curl o Postman. A continuación, se muestra cómo acceder a un endpoint de ejemplo que devuelve un ítem por su ID.

## Ejemplo de uso

Para obtener el ítem con ID 10, visita el siguiente enlace en tu navegador o utiliza una herramienta de línea de comandos:

http://127.0.0.1:8000/items/10

![image](https://github.com/AdrianCMI/FastAPIStarter/assets/74360332/dfd97f17-ce0e-4c5d-9e11-5079296998db)
