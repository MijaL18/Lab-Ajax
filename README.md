# Lab-Ajax

## Descripción
Este documento describe el proceso de creación de una imagen Docker y la ejecución de un contenedor para el entorno del Laboratorio AJAX.

---

## 📦 **Creación de la imagen**

Para crear la imagen Docker, ejecuta el siguiente comando en el directorio donde se encuentra tu archivo `dockerfile5.txt`:

```bash
docker build -f dockerfile5.txt -t dabam .

## 📦 **Creación del contenedor**

Para crear el contenedor Docker, ejecuta el siguiente comando en el directorio donde se encuentra tu archivo `dockerfile5.txt`:

```bash
docker run -d -p 8185:80 -p 2204:22 --name mydabaM dabam
