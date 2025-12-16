

# Preguntas Frecuentes (FAQ)

------------------------------------------------------------------------

## Sobre el Libro

### ¿Qué es Datos++?

Datos++ es un libro digital interactivo diseñado para acompañarte en el
aprendizaje de **Ingeniería de Datos**. Combina explicación teórica y
práctica mediante el enfoque de *literate computing*, integrando texto,
código ejecutable y resultados en un mismo entorno.

### ¿A quién está dirigido este libro?

Datos++ está pensado como material principal para la asignatura
**Ingeniería de Datos** en la Universidad de La Frontera, pero también
es útil para:

- Estudiantes de ingeniería y ciencias de la computación
- Profesionales que quieran fortalecer habilidades en análisis de datos
- Cualquier persona interesada en aprender Python para datos
- Docentes que busquen material de apoyo para sus cursos

### ¿Necesito conocimientos previos?

El libro asume conocimientos básicos de programación. Es recomendable
tener familiaridad con:

- Conceptos básicos de Python
- Fundamentos de programación (variables, funciones, estructuras de
  control)
- Nociones básicas de matemáticas y estadística

------------------------------------------------------------------------

## Uso del Libro

### ¿Cómo puedo usar este libro?

Puedes usar Datos++ de varias maneras:

1.  **Leer en el navegador**: Navega por los capítulos directamente en
    el [sitio web](https://dci-courses.github.io/DatosPlusPlus/)

2.  **Ejecutar notebooks**: Descarga los notebooks `.ipynb` y ejecútalos
    localmente con Jupyter

3.  **Reutilizar código**: Todo el código puede exportarse, copiarse o
    adaptarse para tus propios proyectos

4.  **Material docente**: Las unidades funcionan como material de apoyo
    para clases

### ¿Cómo ejecuto los notebooks localmente?

**Opción 1: Dev Containers (Recomendado)**

1.  Instala [Docker](https://www.docker.com/get-started) y [VS
    Code](https://code.visualstudio.com/)

2.  Instala la extensión [Dev
    Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

3.  Clona el repositorio:

    ``` bash
    git clone https://github.com/dci-courses/DatosPlusPlus.git
    cd DatosPlusPlus
    code .
    ```

4.  En VS Code, presiona `Ctrl+Shift+P` y selecciona “Dev Containers:
    Rebuild and Reopen in Container”

**Opción 2: Instalación Manual**

1.  Clona el repositorio
2.  Crea un entorno virtual de Python 3.10+
3.  Instala las dependencias: `pip install -r requirements.txt`
4.  Ejecuta Jupyter: `jupyter notebook`

### ¿El libro funciona en Windows, Mac y Linux?

Sí. El uso de Dev Containers garantiza un entorno consistente en
cualquier sistema operativo. Si prefieres instalación manual, el código
es compatible con los tres sistemas.

### ¿Puedo trabajar sin conexión a internet?

Sí. Una vez que clones el repositorio y configures el entorno, puedes
trabajar completamente offline.

------------------------------------------------------------------------

## Código y Ejercicios

### ¿En qué lenguaje está el código?

Todo el código está escrito en **Python**, utilizando bibliotecas
estándar del ecosistema de ciencia de datos como pandas, numpy,
matplotlib, entre otras.

### ¿Puedo usar el código en mis propios proyectos?

El código puede ser reutilizado siguiendo los términos de la licencia.
Consulta la [página de licencia](LICENSE.html) para más detalles sobre
atribución y uso permitido.

### ¿Los ejercicios tienen soluciones?

Cada unidad incluye ejercicios guiados con explicaciones paso a paso.
Algunos ejercicios de autoevaluación permiten verificar tus respuestas
directamente en el notebook.

------------------------------------------------------------------------

## Contribuciones y Problemas

### ¿Cómo reporto un error o problema?

1.  Ve a la [página de
    issues](https://github.com/dci-courses/DatosPlusPlus/issues) del
    repositorio
2.  Verifica si el problema ya fue reportado
3.  Si es nuevo, abre un issue describiendo:
    - Qué esperabas que ocurriera
    - Qué ocurrió realmente
    - Pasos para reproducir el problema
    - Tu entorno (sistema operativo, versión de Python, etc.)

### ¿Puedo contribuir al libro?

¡Sí! Aceptamos contribuciones en forma de:

- Correcciones de errores tipográficos o de código
- Mejoras a explicaciones existentes
- Sugerencias de nuevo contenido

Para contribuir, haz un fork del repositorio, realiza tus cambios y
envía un Pull Request.

### ¿Cada cuánto se actualiza el libro?

Datos++ es un proyecto en desarrollo activo. Las actualizaciones se
publican periódicamente conforme se completan nuevas unidades y se
incorporan mejoras.

------------------------------------------------------------------------

## Aspectos Técnicos

### ¿Qué tecnologías usa el libro?

- **Jupyter Book**: Para generar el sitio web estático
- **nbdev**: Para desarrollo basado en notebooks
- **Python 3.10+**: Lenguaje de programación principal
- **GitHub Pages**: Para hosting del sitio web
- **Dev Containers**: Para entornos de desarrollo reproducibles

### ¿Por qué usar Jupyter Notebooks?

Los notebooks permiten:

- Combinar código, texto y visualizaciones en un solo documento
- Ejecutar código de forma interactiva
- Experimentar y modificar ejemplos fácilmente
- Crear material autodocumentado

### ¿Qué hago si un notebook no ejecuta correctamente?

1.  Verifica que estés usando Python 3.10 o superior
2.  Asegúrate de tener todas las dependencias instaladas
3.  Intenta reiniciar el kernel y ejecutar las celdas desde el inicio
4.  Si el problema persiste, [reporta un
    issue](https://github.com/dci-courses/DatosPlusPlus/issues)

------------------------------------------------------------------------

## Licencia y Atribución

### ¿Bajo qué licencia está el libro?

El contenido está bajo licencia [Creative Commons
Atribución–NoComercial–SinDerivadas 4.0 Internacional (CC BY-NC-ND
4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).

### ¿Cómo cito este libro?

    Valenzuela, P., Negrier, M., & Arias, K. (2025). Datos++: Un Puente entre la Teoría y la Práctica. 
    Universidad de La Frontera. https://dci-courses.github.io/DatosPlusPlus/

### ¿Puedo usar el material en mis clases?

Sí, siempre que respetes los términos de la licencia CC BY-NC-ND 4.0:

- **Atribución**: Debes dar crédito apropiado a los autores
- **NoComercial**: No puedes usar el material con fines comerciales
- **SinDerivadas**: No puedes distribuir versiones modificadas

------------------------------------------------------------------------

## Contacto

### ¿Cómo contacto a los autores?

Para consultas generales, abre un [issue en
GitHub](https://github.com/dci-courses/DatosPlusPlus/issues) o contacta
a los autores a través de la Universidad de La Frontera.

### ¿Dónde puedo seguir las novedades del proyecto?

- [Repositorio en GitHub](https://github.com/dci-courses/DatosPlusPlus)
- [Notas de versión](ReleaseNotes.html)
