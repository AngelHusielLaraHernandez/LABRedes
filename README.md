# Laboratorio de Redes

![LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white)
![Redes](https://img.shields.io/badge/Networking-005571?style=for-the-badge&logo=cisco&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En_Progreso-blue?style=for-the-badge)

¡Bienvenido al repositorio de las prácticas del **Laboratorio de Redes**! 💻📡 
Aquí encontrarás todos los reportes y documentos desarrollados durante el semestre. Todo el contenido está redactado y maquetado de forma profesional utilizando **LaTeX**.

---

##  Organización del Proyecto

El proyecto está dividido en carpetas por cada práctica realizada. Cada una funciona de manera independiente y contiene su propio archivo fuente junto con sus respectivos recursos visuales correspondientes. 

*  **[Practica 1](./Practica1)**: *Aquí puedes describir brevemente de qué trató la práctica 1.*
*  **[Practica 2](./Practica2)**: *Aquí puedes describir brevemente de qué trató la práctica 2.*
*  **[Practica 3](./Practica3)**: *Aquí puedes describir brevemente de qué trató la práctica 3.*
*  **[Practica 4](./Practica4)**: *Aquí puedes describir brevemente de qué trató la práctica 4.*

###  ¿Qué hay dentro de cada carpeta?

Si exploras cualquiera de las carpetas de las prácticas, encontrarás la siguiente estructura:
- `miau.tex`: **El archivo principal**. Aquí reside todo el código de LaTeX con la redacción del reporte.
- `image/`: El directorio que guarda todas las imágenes, diagramas y capturas de pantalla usadas en la práctica.
- `miau.aux`, `miau.toc`, etc.: Archivos auxiliares que LaTeX genera de forma automática al compilar (estos son ignorados por Git).

---

##  ¿Cómo compilar los reportes?

Para transformar el código a un documento PDF hermoso, necesitas tener LaTeX instalado (como TeX Live o MiKTeX) o usar un entorno web como [Overleaf](https://www.overleaf.com/).

Si compilas desde tu computadora, simplemente abre tu terminal en la carpeta de la práctica correspondiente y ejecuta:

```bash
pdflatex miau.tex
```
*( Tip: Es recomendable correr el comando un par de veces para que los índices y las referencias cruzadas se generen correctamente).*

---

##  Control de Versiones (.gitignore)

Se ha configurado un archivo `.gitignore` especialmente pensado para **LaTeX**. Esto significa que cuando hagas tus `git add`, tu repositorio se mantendrá limpio y **NO** subirá archivos basura generados durante la compilación (`.aux`, `.fdb_latexmk`, `.fls`, `.toc`, `.log`, etc.). Solo se guardará lo verdaderamente importante: tu código `.tex` y tus imágenes.
