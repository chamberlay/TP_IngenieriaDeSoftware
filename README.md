# TP Ingeniería de Software - Git y Docker

## Descripción

Este proyecto consiste en un Curriculum Vitae Web desarrollado utilizando **HTML5** y **CSS3**. Como parte de la evolución del proyecto, se incorporó una segunda página denominada **Proyectos**, permitiendo presentar algunos de los trabajos realizados durante la carrera.

El objetivo principal del trabajo práctico es aplicar conceptos de control de versiones con **Git**, trabajo con ramas (**Branches**), integración mediante **Merge**, contenerización con **Docker** y publicación tanto del código como de la imagen Docker.

## Tecnologías utilizadas

* HTML5
* CSS3
* Git
* GitHub
* Docker
* Docker Hub
* Nginx

---

## Requisitos previos

Antes de ejecutar el proyecto es necesario tener instalado:

* Git
* Docker Desktop

---

## Ejecución de la aplicación

### Opción 1 - Ejecución local

1. Clonar el repositorio:

```bash
git clone https://github.com/chamberlay/TP_IngenieriaDeSoftware.git
```

2. Ingresar a la carpeta del proyecto:

```bash
cd TP_IngenieriaDeSoftware
```

3. Abrir el archivo `index.html` con cualquier navegador web.

---

### Opción 2 - Ejecución con Docker

#### Construir la imagen

```bash
docker build -t cv-web .
```

#### Ejecutar el contenedor

```bash
docker run -d -p 8080:80 --name cv-container cv-web
```

#### Acceder a la aplicación

Abrir el navegador y dirigirse a:

```text
http://localhost:8080
```

---

## Repositorio en GitHub

https://github.com/chamberlay/TP_IngenieriaDeSoftware

## Imagen publicada en Docker Hub

https://hub.docker.com/r/cha1504/tp_ingenieriadesoftware

## GitHub Pages

https://chamberlay.github.io/TP_IngenieriaDeSoftware/

---

## Autor

**Chamberlay Vega Gomez**

Tecnicatura Superior en Desarrollo de Software - ISTEA

Trabajo Práctico - Git y Docker
