# Mapa del Sitio

## Navegación del Libro

Los capítulos de este libro están organizados por técnicas de minería de datos y machine learning. Cada sección incluye ejemplos prácticos con código ejecutable en Python.

---

## Tabla de Contenidos

### [Inicio](index.html)

Página principal con información general sobre el libro Datos++, sus objetivos, público objetivo y cómo utilizarlo. Incluye información sobre los autores y el financiamiento del proyecto DID25-0004.

---

### Parte I: Clasificación

Técnicas de aprendizaje supervisado para categorizar datos en clases predefinidas. Esta sección aborda problemas reales de ciberseguridad y calidad de software.

#### [Detección de Keyloggers](classification/classification_keylogger.html)

Clasificación de software malicioso tipo keylogger mediante técnicas de machine learning. Se trabaja con un dataset de Kaggle que contiene características de spyware diseñado para registrar pulsaciones de teclado. El notebook incluye:

- Análisis exploratorio de datos (EDA)
- Preparación y limpieza de datos
- Entrenamiento de múltiples modelos
- Evaluación con métricas de precisión, recall y F1-score
- Técnicas de balanceo de clases

#### [Detección de Ransomware](classification/classification_ransomware.html)

Análisis y clasificación de malware tipo ransomware utilizando un dataset de 2024 con 21,752 muestras balanceadas. El dataset incluye 26 familias de malware, con énfasis en ransomware conocido como Cerber, DarkSide, GandCrab, Ryuk y WannaCry. El notebook cubre:

- Exploración del dataset de malware
- Ingeniería de características
- Comparación de modelos de clasificación
- Matriz de confusión y análisis de errores
- Estrategias de balanceo de datos

#### [Análisis de Defectos de Software](classification/classification_software_defects.html)

Predicción de defectos en código fuente multilenguaje (Python, Java, JavaScript, C, C++, Go, Rust) utilizando características basadas en AST (Abstract Syntax Tree). El dataset sintético incluye métricas como:

- Conteo de tokens
- Número de estructuras de control (ifs, loops)
- Complejidad del código
- Predicción binaria: código con defectos vs. código limpio

---

### Parte II: Clustering

Técnicas de aprendizaje no supervisado para agrupar datos sin etiquetas predefinidas. Esta sección explora el clustering aplicado a imágenes.

#### [Clustering de Imágenes: Perros y Gatos](clustering/01_ejemplo_1.1.html)

Introducción al clustering de imágenes utilizando un dataset clásico de perros y gatos. Se simula un escenario sin etiquetas para demostrar técnicas de aprendizaje no supervisado. El notebook incluye:

- Preprocesamiento de imágenes
- Extracción de características
- Aplicación de algoritmos de clustering
- Validación de resultados usando etiquetas originales

#### [Clustering de Imágenes: Videojuegos](clustering/02_ejemplo_2.1.html)

Clustering de capturas de pantalla de videojuegos populares (Minecraft, Fortnite, Apex Legends, Genshin Impact, entre otros). Diseñado para ejecutarse en Google Colab con GPU. El notebook aborda:

- Descarga de dataset desde Kaggle API
- Procesamiento de imágenes de alta resolución
- Agrupamiento de screenshots por juego
- Evaluación de calidad del clustering

#### [Clustering de Videojuegos: Implementación Alternativa](clustering/03_ejemplo_2.2.html)

Segunda implementación del problema de clustering de videojuegos utilizando un algoritmo alternativo. Permite comparar diferentes enfoques de clustering en el mismo dataset. Incluye:

- Algoritmo de clustering diferente
- Comparación de rendimiento
- Análisis de ventajas y desventajas de cada enfoque

---

### Parte III: Reglas de Asociación

Técnicas de minería de datos para descubrir relaciones interesantes entre variables en conjuntos de datos transaccionales.

#### [Introducción a las Reglas de Asociación](association-rules/00_ejemplo_1.1.html)

Fundamentos teóricos de las reglas de asociación con un ejemplo didáctico de supermercado. Cubre las métricas fundamentales:

- **Soporte (Support)**: Frecuencia de aparición de un conjunto de ítems
- **Confianza (Confidence)**: Probabilidad condicional de compra
- **Lift**: Relación entre ocurrencias de ítems

Incluye ejemplo paso a paso con transacciones de Leche, Pan, Mantequilla y Manzana.

#### [Implementación con Python](association-rules/02_ejemplo_1.2.html)

Implementación práctica del ejemplo teórico utilizando Python y la biblioteca `mlxtend`. Cubre:

- Uso de `TransactionEncoder` para convertir transacciones en matrices booleanas
- Aplicación del algoritmo Apriori
- Generación y filtrado de reglas de asociación
- Interpretación de resultados

#### [Ejercicio Práctico](association-rules/03_ejercicio.html)

Ejercicio para practicar la identificación de reglas de asociación con un conjunto extendido de transacciones que incluye nuevos productos como Cereal y Galletas.

---

## Dependencias entre Capítulos

![](https://github.com/dci-courses/DatosPlusPlus/blob/main/sitemap-png.png?raw=true){width=80% fig-align="center"}

Las tres secciones principales (Clasificación, Clustering, Reglas de Asociación) son independientes entre sí y pueden estudiarse en cualquier orden.

---

## Rutas de Aprendizaje Sugeridas

### Ruta Completa (Recomendada)

Para una comprensión integral de las técnicas de minería de datos:

1. Inicio → Reglas de Asociación (conceptos básicos)
2. Clasificación (aprendizaje supervisado)
3. Clustering (aprendizaje no supervisado)

### Ruta: Ciberseguridad

Si tu interés está en aplicaciones de seguridad informática:

1. Detección de Keyloggers
2. Detección de Ransomware
3. Análisis de Defectos de Software

### Ruta: Procesamiento de Imágenes

Para enfocarte en análisis de imágenes con machine learning:

1. Clustering de Perros y Gatos
2. Clustering de Videojuegos
3. Implementación Alternativa

### Ruta: Análisis de Transacciones

Para análisis de datos de ventas o comportamiento:

1. Introducción a Reglas de Asociación
2. Implementación con Python
3. Ejercicio Práctico

---

## Sobre el Libro

Material complementario y recursos adicionales.

- [**Licencia**](sobre-el-libro/LICENSE.html) — Información sobre CC BY-NC-ND 4.0
- [**Notas de Versión**](ReleaseNotes.html) — Historial de cambios y actualizaciones
- [**Preguntas Frecuentes**](FAQ.html) — FAQ sobre uso, instalación y contribuciones

---

## Recursos Externos

- **Repositorio GitHub**: [github.com/dci-courses/DatosPlusPlus](https://github.com/dci-courses/DatosPlusPlus)
- **Issues y Sugerencias**: [GitHub Issues](https://github.com/dci-courses/DatosPlusPlus/issues)
- **Universidad de La Frontera**: [www.ufro.cl](https://www.ufro.cl)

---

## Licencia

El contenido de este proyecto está licenciado bajo la licencia [Creative Commons Atribución–NoComercial–SinDerivadas 4.0 Internacional (CC BY-NC-ND 4.0)](https://creativecommons.org/licenses/by-nc-nd/4.0/).
