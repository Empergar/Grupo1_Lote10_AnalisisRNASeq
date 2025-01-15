# Grupo1_Lote10_AnalisisRNASeq

## Descripción
Este proyecto forma parte de la actividad grupal de la asignatura *Introducción a la Programación Científica*.  
El objetivo principal es analizar la expresión génica de un conjunto de muestras utilizando datos de RNA-Seq, aplicando herramientas bioinformáticas y técnicas de control de versiones con Git y GitHub.

## Índice
1. [Objetivos](#objetivos)
2. [Estructura del proyecto](#estructura-del-proyecto)
3. [Instrucciones de uso](#instrucciones-de-uso)
4. [Colaboradores](#colaboradores)
5. [Licencia](#licencia)

## Objetivos
- Cuantificar la expresión génica: Medir los niveles de expresión de genes e identificar las diferencias.
- Análisis diferencial de expresión: Comparar la expresión entre grupos y encontrar genes claves.
- Descubrir nuevos genes/transcritos: Identificar genes no anotados y ARN no codificantes.
- Analizar vías biológicas: Relacionar genes con procesos y redes biológicas importantes.


## Estructura del proyecto 

```bash
Grupo1_Lote10_AnalisisRNASeq/
├── LICENSE
├── README.md
├── Resultados/
│   └── resultados.txt
├── analisis/
│   └── .gitkeep
├── Data/
│   └── data.csv
├── scripts/
│   └── pipeline.Rmd
```

## Instrucciones de uso
El repositorio consta de dos carpetas principales que son "analisis" y "Resultados".

En la carpeta "analisis" hay dos subcarpetas "data" y "scripts" que contienen los datos y los programas para el análisis de RNAseq. 

En la carpeta "Resultados" aparcen los resultados del análisis. 

### **1. Clonar el repositorio**
Primero, clona este repositorio en tu máquina local utilizando la terminal. Si no tienes Git instalado, asegúrate de instalarlo previamente desde [Git](https://git-scm.com/).

1. Abre la terminal en tu computadora.
2. Navega al directorio donde deseas clonar el repositorio:

   ```bash
   cd /ruta/donde/quieres/clonar
   ```
4. Clona el repositorio con el siguiente comando:

   ```bash
   git clone https://github.com/TuUsuario/Grupo1_Lote10_AnalisisRNASeq.git
   ```
5. Cambia al directorio del proyecto:

   ```bash
   cd Grupo1_Lote10_AnalisisRNASeq
   ```
   
### **2. Preparar el entorno**
Antes de ejecutar el análisis, asegúrate de que tienes las herramientas necesarias:
1. **Instalar R y RStudio:**
   - Descarga e instala [R](https://cran.r-project.org/) y [RStudio](https://posit.co/download/rstudio-desktop/).

2. **Instalar las librerías necesarias en R:**
   Abre RStudio y ejecuta lo siguiente en la consola para instalar los paquetes necesarios:

   ```R
   install.packages(c("DESeq2", "ggplot2"))
   ```
### **3. Ejecutar el pipeline**
1. Abre RStudio.
2. Navega a la carpeta `scripts` del proyecto dentro de RStudio:
   - En la barra superior, haz clic en **File > Open File**.
   - Selecciona el archivo `pipeline.Rmd` dentro de la carpeta `scripts`.

3. Ejecuta el archivo paso a paso o genera un informe completo:
   - Para ejecutar el código paso a paso, usa **Ctrl+Enter** (Windows/Linux) o **Cmd+Enter** (Mac) en cada bloque de código.
   - Para generar el informe completo, haz clic en el botón **Knit** en la barra superior de RStudio. Esto creará un archivo HTML con el análisis completo.


### **4. Verificar los resultados**
1. Los resultados generados por el pipeline se guardarán en la carpeta `resultados/` como el archivo `resultados.txt`.
2. Puedes abrir este archivo en cualquier editor de texto o importarlo en herramientas para análisis adicional.

### **5. Actualizar el repositorio**
Si otros colaboradores han realizado cambios en el repositorio, actualiza tu copia local con:

```bash
git pull
```

## Colaboradores

AHai22 - Ángela Hairong Jiménez Santamaría.

Empergar - Emma Pérez García.

NuriaAnt - Nuria Antón Baltanás. 

Banboru - José Antonio Ferrandis Conca.

## Licencia

Se ha hecho uso de la licencia MIT, esta una de las licencias de software libre más populares y simples. Permite a otros usar, modificar, distribuir, y sublicenciar tu código con muy pocas restricciones, fomentando la colaboración y la reutilización del software.
