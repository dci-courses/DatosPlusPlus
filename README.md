# DatosPlusPlus

Bienvenido/a al repositorio de **DatosPlusPlus**.  
Este proyecto está preparado para que trabajes en un entorno de desarrollo completamente configurado usando **Dev Containers** en Visual Studio Code.

## 📋 Prerrequisitos

Antes de comenzar, asegúrate de tener instalado lo siguiente:

### 1. Docker
Descárgalo desde: [https://www.docker.com/get-started](https://www.docker.com/get-started)  
> **Importante:** Asegúrate de que Docker esté corriendo correctamente en tu sistema.

### 2. Visual Studio Code
Descárgalo desde: [https://code.visualstudio.com/](https://code.visualstudio.com/)

### 3. Extensión Dev Containers
Instálala desde: [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## 🚀 Pasos para comenzar

### 1. Clona este repositorio

```bash
git clone https://github.com/dci-courses/DatosPlusPlus.git
cd DatosPlusPlus
```

### 2. Abre el proyecto en VS Code

```bash
code .
```

### 3. Reconstruye y abre el contenedor de desarrollo

Dentro de VS Code:

1. Presiona `Ctrl + Shift + P` (o `Cmd + Shift + P` en Mac)
2. Escribe y selecciona: `Dev Containers: Rebuild and Reopen in Container`
![Abrir como Dev Container](https://github.com/dci-courses/DatosPlusPlus/blob/main/Abrir%20como%20Dev%20Container.png?raw=true)

Esto reiniciará VS Code dentro de un contenedor Docker con el entorno preconfigurado.

### 4. Configura el kernel de Jupyter

1. Abre cualquier notebook `.ipynb`
2. Al ejecutar una celda por primera vez, selecciona el kernel: **Python (DatosPlusPlus)**
![Seleccionar Kernel](https://github.com/dci-courses/DatosPlusPlus/blob/main/Seleccionar%20Kernel.png?raw=true)

---

# 🧭 Flujo de trabajo con nbdev

A continuación se detalla el flujo básico para trabajar con nbdev en este proyecto:

## 1. Crear o editar notebooks

Los notebooks se encuentran en la carpeta principal o en `nbs/`.
Puedes crear nuevos archivos `.ipynb` o modificar los existentes.

**Ejemplo de estructura:**

```
nbs/
 ├── 00_introduccion.ipynb
 ├── 01_limpieza_datos.ipynb
 └── 02_modelos.ipynb
```

Cada notebook puede contener:

- Código Python
- Celdas Markdown con documentación
- Pruebas (assert, doctest, etc.)

## 2. Verificar y limpiar notebooks

Antes de subir cambios, limpia las salidas y verifica la consistencia:

```bash
nbdev_clean
```

## 3. Previsualizar cambios

Una vez todo esté listo, antes de subir los cambios es necesario previsualizarlos para evitar cualquier error en producción:

```bash
nbdev_preview
```

## 💡 Soporte

Si tienes alguna pregunta o problema, por favor abre un [issue](../../issues) en este repositorio.
