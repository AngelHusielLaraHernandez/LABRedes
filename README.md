# Laboratorio de Redes

![LaTeX](https://img.shields.io/badge/LaTeX-47A141?style=for-the-badge&logo=LaTeX&logoColor=white)
![Redes](https://img.shields.io/badge/Networking-005571?style=for-the-badge&logo=cisco&logoColor=white)
![Estado](https://img.shields.io/badge/Estado-En_Progreso-blue?style=for-the-badge)


Aquí encontrarás todos los reportes y documentos desarrollados durante el semestre. Todo el contenido está redactado y maquetado de forma profesional utilizando **LaTeX**.

---

##  Organización del Proyecto

El proyecto está dividido en carpetas por cada práctica realizada. Cada una funciona de manera independiente y contiene su propio archivo fuente junto con sus respectivos recursos visuales correspondientes. 

*  **[Practica 1](./Practica1)**: Aspectos físicos de las redes, enfocándose en medios de transmisión como el cable UTP, STP, fibra óptica, normativas de cableado (T568A/T568B) y la Capa 1 del modelo OSI.
*  **[Practica 2](./Practica2)**: Organizaciones y estándares de telecomunicaciones. Análisis de las funciones de organismos como ANSI, EIA y TIA en el desarrollo de normas para cableado estructurado.
*  **[Practica 3](./Practica3)**: Sistemas de canalización y subsistemas de cableado estructurado (norma ANSI/TIA 569), diseño de cuartos de telecomunicaciones, cálculo de canaletas, equipos activos/pasivos y la regla 5-4-3.
*  **[Practica 4](./Practica4)**: Topologías lógicas y la Capa 2 del modelo OSI. Diferencias entre hub y switch, método de acceso CSMA/CD, dominios de colisión, comunicación Half/Full Duplex y conexiones en cascada.
*  **[Practica 5](./Practica5)**: Direccionamiento lógico y físico. Clasificación de direcciones IP, máscaras de subred, funciones de DNS/DHCP/Gateway, y comandos básicos de diagnóstico de red como el comando `ping`.

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
