# Cómo instalar Streamlit con un entorno virtual

## Requisitos previos

- Python 3.8 o superior instalado
- Una terminal

---

## 1. Crea una carpeta para el proyecto

```bash
mkdir mi-app
cd mi-app
```

## 2. Crea el entorno virtual

```bash
python -m venv venv
```

Esto crea una carpeta llamada `venv` dentro de tu proyecto.

## 3. Activa el entorno virtual

**Mac / Linux:**
```bash
source venv/bin/activate
```

**Windows:**
```bash
venv\Scripts\activate
```

Sabrás que está activo cuando veas `(venv)` al inicio de tu terminal.

## 4. Instala Streamlit

```bash
pip install streamlit
```

## 5. Verifica la instalación

```bash
streamlit hello
```

Esto abre una app de demo en el navegador. Si carga, todo funciona.

## 6. Crea tu app

Crea un archivo `app.py`:

```python
import streamlit as st

st.title("Mi primera app")
st.write("Hola, mundo!")
```

## 7. Ejecuta tu app

```bash
streamlit run app.py
```

La app se abre automáticamente en `http://localhost:8501`.

## Desactivar el entorno

```bash
deactivate
```

---

## Estructura del proyecto

```
mi-app/
├── venv/
└── app.py
```

## Link a la presentación

https://www.figma.com/deck/ZDXeZvxct4a1DpnO473k1n/Streamlit-pildora?node-id=49-77&t=SqJFAKZwo6OKhsOU-1
