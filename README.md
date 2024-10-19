# Grupo 10
Este es el repositorio del Grupo 10 cuyos integrantes son:
* Luis González - 202021002-0
* Valentina Ibacache- 202173136-9
* Daniela Aguilar - 202111060-7
* Benjamín Mac-kay - 202204098-k
* **Tutor:** Ariane Carvajal

## Wiki
Puede acceder a la Wiki mediante el siguiente [enlace](https://gitlab.com/anon369mad/grupo10-2024-proyinf/-/wikis/home).

## Video Prototipo
En el siguiente enlace se puede visualizar el video de presentación del prototipo [enlace](https://www.youtube.com/watch?v=YPCQg1orsf8) (hasta esta entrega el prototipo es no funcional).

## Aspectos técnicos relevantes

Elegimos como tecnología frontend "Angular", el cuál sirve para crear aplicaciónes web de una sola página. Además creamos una nueva rama llamada "develop" donde están todos los archivos que se ocupan en el levantamiento del proyecto.

## Pasos para levantar Proyecto

### 1. Clonar el repositorio
Primero clone el repositorio en su máquina local:

```bash
git clone https://gitlab.com/anon369mad/grupo10-2024-proyinf.git
cd grupo10-2024-proyinf
```
Una vez hecho esto, cambie la rama a "develop".

### 2. Docker Desktop
Para iniciar el proyecto, haremos uso de la herramienta Docker Desktop, por lo que tenemos que asegurarnos de que la aplicación de escritorio se esté ejecutando.

### 4. Construir y Levantar el Proyecto
Una vez asegurados de que Docker Desktop esté en funcionamiento, abrimos la terminal y escribimos el siguiente snippet:

```bash
docker-compose up --build
```
Después, cerramos la terminal.

### 5. Inicializar el proyecto
Para iniciar el proyecto, se utiliza:

```bash
docker-compose up
```

### 6. Verificar el Funcionamiento
Una vez que el proyecto esté en ejecución, visita http://127.0.0.1:8000/docs en tu navegador.