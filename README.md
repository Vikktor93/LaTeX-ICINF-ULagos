# Plantillas LaTeX - ICINF Universidad de Los Lagos

Este repositorio contiene una colección de plantillas en LaTeX diseñadas para facilitar la escritura de documentos académicos, informes técnicos y proyectos de titulación para los estudiantes de Ingeniería Civil en Informática de la **Universidad de Los Lagos**. 

El objetivo es estandarizar los formatos de entrega y permitir que los estudiantes se enfoquen en el contenido, dejando el diseño y la estructura en manos de LaTeX.

---

## 🚀 Requisitos Previos (Windows 11)

Para utilizar estas plantillas de manera local en tu computador, debes instalar los siguientes componentes en este orden:

1.  **Distribución LaTeX:** Descargar e instalar [MiKTeX](https://miktex.org/download). 
    * *Importante:* Durante la instalación, en la opción de "instalar paquetes faltantes", selecciona **"Always install missing packages on-the-fly"** para evitar errores de compilación.
2.  **Motor de Scripts:** Instalar [Strawberry Perl](https://strawberryperl.com/). Es fundamental para que las herramientas de limpieza y formato de código funcionen en Windows.
3.  **Editor de Código:** Instalar [Visual Studio Code](https://code.visualstudio.com/).
4.  **Extensión de LaTeX:** Dentro de VS Code, instala la extensión **LaTeX Workshop** (de James Yu).

---

## 🛠️ Configuración de VS Code

Para una experiencia óptima, abre la carpeta raíz de este repositorio en VS Code. La extensión detectará automáticamente tus archivos `.tex`.

* **Compilación:** Al guardar cualquier archivo con `Ctrl + S`, el sistema generará el PDF automáticamente en la misma carpeta.
* **Depuración:** Si el sistema detecta advertencias (como tamaños de encabezado o citas faltantes), revisa la pestaña **"Problemas"** en la parte inferior del editor.
* **Visualización:** El PDF resultante aparecerá en una pestaña lateral dentro del mismo VS Code.

---

## 📂 Plantillas Disponibles

A continuación, se detallan las plantillas incluidas actualmente en el repositorio:

| Carpeta | Descripción | PDF de Muestra |
| :--- | :--- | :---: |
| `Articulo 2 columnas` | Formato tipo "paper" para publicaciones o congresos. | ❌ |
| `Carta / Memorandum` | Plantillas para comunicación administrativa formal. | ❌ |
| `Curriculum` | Plantilla profesional para CV de estudiantes y egresados. | ❌ |
| `Ejemplo_Informe_BD` | Estructura para informe del proyecto de bases de datos. | ❌ |
| `Evaluaciones` | Formato para evaluaciones oficiales, ayudantatias o tutorias. | ❌ |
| `Informes` | Estructura básica para informes de asignaturas disciplinares. | ❌ |
| `Poster` | Plantilla para el poster final del Proyecto Integrador de 1er Semestre. | ❌ |
| `Prácticas` | Plantilla para el informe de práctica intermedia y profesional. | ❌ |
| `Presentaciones Beamer` | Diapositivas académicas con los colores de la universidad. | ❌ |
| `Propuesta Tesis` | Formato inicial para la inscripción de temas de proyecto de título. | ❌ |
| `Proyecto de Titulacion` | Formato oficial para tesis y memorias de título. | [✅](Vista%20Previa/Proyecto%20de%20Titulacion.pdf)|
| `Tareas` | Formato básico para tareas de asiganturas de la carrera. | [✅](Vista%20Previa/Tareas.pdf) |


---

## 📖 Instrucciones de Uso

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/Vikktor93/LaTeX-ICINF-ULagos.git
    ```
2.  **Navegar a la plantilla:** Abre la carpeta de la plantilla que deseas usar (por ejemplo: `Proyecto de Titulacion`).
3.  **Editar el contenido:** Abre el archivo raíz (por ejemplo: `TrabajoTitulacion.tex`) y modifica tus datos personales en el preámbulo.
4.  **Generar PDF:** Guarda los cambios. El PDF se actualizará automáticamente y podrás verlo en tiempo real.

---

## 🤝 Soporte y Contacto

Este repositorio es administrado por el **Profesor Víctor Saldivia Vera**. 

Si eres estudiante y encuentras algún error en las macros o tienes sugerencias para nuevas plantillas, por favor abre un **Issue** en este repositorio o contacta directamente a través de los canales institucionales.

---
2026 - Universidad de Los Lagos, Castro, Chile.