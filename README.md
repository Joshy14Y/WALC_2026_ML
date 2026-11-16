# WALC 2026

## Ejecutar los notebooks en VS Code con uv

Requisitos: tener `uv`, Python 3.12 o superior y VS Code con las extensiones **Python** y **Jupyter** de Microsoft instaladas.

Desde la carpeta raíz del proyecto, instala las dependencias:

```bash
uv sync --locked
```

Abre la carpeta del proyecto en VS Code. Si tienes el comando `code` disponible, puedes usar:

```bash
code .
```

Los notebooks del taller están en la carpeta `notebooks/`, organizados en subcarpetas por día.

1. Explora `notebooks/` y abre el archivo `.ipynb` que corresponda a la actividad.
2. En el selector de kernel del notebook, elige el entorno de Python de `.venv`.
3. Ejecuta las celdas en orden, de arriba hacia abajo.

No es necesario activar el entorno virtual: `uv` lo gestiona automáticamente en `.venv`.
