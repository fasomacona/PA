# Tema 1 – Fundamentos de Programación Avanzada y Manipulación de Datos

**Asignatura:** Programación Avanzada (GAB-2402)  
**Carrera:** Ingeniería Informática  
**Especialidad:** Gestión y Analítica Avanzada de Datos  
**Institución:** Tecnológico de Estudios Superiores de Chalco

---

## Descripción

Sitio web didáctico que desarrolla de forma detallada el **Tema 1** de la asignatura:

1. **1.1** Introducción a la programación avanzada con Python  
2. **1.2** Manipulación avanzada de datos con NumPy y Pandas  
3. **1.3** Operaciones de limpieza, transformación y preparación de datos  

Incluye una **práctica completa en Jupyter Notebook** lista para resolver.

---

## Estructura del repositorio

```
tema1-programacion-avanzada/
├── index.html                  # Página principal
├── 01-introduccion.html        # Subtema 1.1
├── 02-numpy-pandas.html        # Subtema 1.2
├── 03-limpieza-datos.html      # Subtema 1.3
├── practica.html               # Guía de la práctica
├── css/
│   └── styles.css              # Estilos
├── notebooks/
│   └── practica_tema1.ipynb    # Notebook de ejercicios y caso práctico
└── README.md
```

---

## Cómo visualizar el sitio

### Opción 1 – Local
Abre `index.html` directamente en tu navegador o usa un servidor local:

```bash
# Con Python
python -m http.server 8000

# Luego visita http://localhost:8000
```

### Opción 2 – GitHub Pages
1. Sube este repositorio a GitHub.
2. Ve a **Settings → Pages**.
3. Selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
4. El sitio quedará disponible en `https://tu-usuario.github.io/nombre-repo/`.

---

## Cómo ejecutar la práctica

```bash
# 1. Crear entorno virtual (recomendado)
python -m venv venv
source venv/bin/activate          # Linux/macOS
# venv\Scripts\activate           # Windows

# 2. Instalar dependencias
pip install numpy pandas matplotlib seaborn scipy scikit-learn jupyter

# 3. Lanzar Jupyter
jupyter lab
# o
jupyter notebook
```

Abre el archivo `notebooks/practica_tema1.ipynb` y resuelve los ejercicios marcados con `# TODO`.

También puedes subirlo a **Google Colab**.

---

## Competencias que se desarrollan

- Utilizar sintaxis avanzada de Python para la manipulación y análisis de datos.
- Implementar operaciones de limpieza, transformación y preparación de datos con NumPy y Pandas.
- Escribir código limpio, eficiente y documentado.

---

## Bibliografía recomendada

- McKinney, W. (2017). *Python for Data Analysis*. O’Reilly Media.
- VanderPlas, J. (2016). *Python Data Science Handbook*. O’Reilly Media.
- Documentación oficial: [NumPy](https://numpy.org/doc/) · [Pandas](https://pandas.pydata.org/docs/) · [Python](https://docs.python.org/3/)

---

Material generado para uso académico · Listo para subir a GitHub.
