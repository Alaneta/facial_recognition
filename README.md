# Facial Recognition Application
## Introducción

El objetivo de esta aplicación es poder realizar el reconocimiento facial de las imágenes que se dispongan con la base de
imágenes cargadas.

En principio, la aplicación contiene un diccionario de referencias conformada por imágenes de la popular serie The Office.
Estas imágenes se encuentran cargadas en /images/imagenes_referencia_reconocimiento_facial.
Finalmente el reconocimento facial se realiza sobre las imágenes images/dwight.jpg y images/the_office.jpg


## Instalación Local (Linux)

1. Clonar el repositorio de la aplicación
   ```sh
   git clone https://github.com/Alaneta/facial_recognition.git
   ```

2. Construir virtual environment con sus dependencias
   ```sh
   ./init.sh
   ```

## Ejecución local del script

   Iniciar virtual environment y ejecutar main.py
   ```sh
   source venv/bin/activate
   ```
   ```sh
   python3 main.py
   ```

## Aclaraciones

Si se va a incluir alguna librería nueva en el desarrollo, recordar agregar esa librería al archivo de dependencias
requirements.txt.
Se puede re-crear este archivo con los siguientes comandos:

 ``` sh
 pip install pipreqs
   ```

 ``` sh
 pipreqs /home/project/location
   ```

## Documentación del proyecto

[Trabajo Práctico](https://docs.google.com/document/d/1R8se3AIHBFK0DZxLJtxon7IMwLG42zj6bBZzhM_qkFA/edit?usp=sharing)

## Autor

* **Alan Camussi** - Desarrollador  - [Alaneta](https://github.com/Alaneta)
* **Fernando Lagoa** - Analista Funcional  - [LagFer](https://github.com/LagFer)

<p align="right">(<a href="#top">volver a inicio</a>)</p>

<br>
