# Grupo 10
Este es el repositorio del Grupo 10 cuyos integrantes son:
* Luis González - 202021002-0
* Valentina Ibacache- 202173136-9
* Daniela Aguilar - 202111060-7
* Benjamín Mac-kay - 202204098-k
* **Tutor:** Ariane Carvajal

## Wiki
Puede acceder a la Wiki mediante el siguiente [enlace](https://gitlab.com/anon369mad/grupo10-2024-proyinf/-/wikis/home).

## Aspectos técnicos relevantes

Elegimos como tecnología frontend "Angular", el cuál sirve para crear aplicaciónes web de una sola página.

## Pasos para levantar Proyecto

### 1. Clonar el repositorio
Primero clone el repositorio en su máquina local:

```bash
git clone https://gitlab.com/anon369mad/grupo10-2024-proyinf.git
cd grupo10-2024-proyinf
```
Una vez hecho esto, cambie la rama a "develop" e ingrese a la carpeta de la aplicación Angular.

```bash
cd proyecto
```

Se instalan las dependencias de Angular.

```bash
npm install @angular/cli
```

Luego se vuelve a la carpeta de nuestro proyecto.

```bash
cd ..
```

### 2. Docker Desktop y levantamiento del proyecto
Para iniciar el proyecto, haremos uso de la herramienta Docker Desktop, por lo que tenemos que asegurarnos de que la aplicación de escritorio se esté ejecutando utilizando ``docker version`` en la terminal. Se mostrará algo similar a lo siguiente:

```bash
Server: Docker Desktop 4.34.3 (170107)
 Engine:
  Version:          27.2.0
  API version:      1.47 (minimum version 1.24)
  Go version:       go1.21.13
  Git commit:       3ab5c7d
  Built:            Tue Aug 27 14:15:15 2024
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.7.20
  GitCommit:        8fc6bcff51318944179630522a095cc9dbf9f353
 runc:
  Version:          1.1.13
  GitCommit:        v1.1.13-0-g58aa920
 docker-init:
  Version:          0.19.0
  GitCommit:        de40ad0
```

### Caso 1: Primera vez levantando el proyecto
Una vez asegurados de que Docker Desktop esté en funcionamiento, abrimos la terminal y escribimos el siguiente snippet:

```bash
docker-compose up --build
```
Para iniciar el proyecto, se utiliza:

```bash
docker-compose up
```
### Caso 2: El proyecto ya fue levantado previamente
Ocupar el siguiente comando (luego escribir "y" en la terminal):

```bash
docker system prune -a
```
Reiniciamos Docker y verificamos que no tenga ningún contenedor, imagen, volumen o build (se eliminan si todavía están). 
Luego, escribimos en la terminal el siguiente comando:

```bash
docker-compose up --build
```
Para iniciar el proyecto, se utiliza:

```bash
docker-compose up
```

### 3. Verificar el Funcionamiento
Una vez que el proyecto esté en ejecución, visita http://127.0.0.1:8000 para verificar el funcionamiento en tu navegador.
Para visitar la página de inicio de nuestro proyecto, visita http://127.0.0.1:80. Para ingresar a las vistas seleccionar el rol que se desea en pantalla y este llevará a lo correspondiente.

