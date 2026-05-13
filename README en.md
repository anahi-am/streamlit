# How to install Streamlit with a virtual environment

## Prerequisites

- Python 3.8 or higher installed
- A terminal

---

## 1. Create a project folder

```bash
mkdir my-app
cd my-app
```

## 2. Create the virtual environment

```bash
python -m venv venv
```

This creates a folder called `venv` inside your project.

## 3. Activate the virtual environment

**Mac / Linux:**
```bash
source venv/bin/activate
```

**Windows:**
```bash
venv\Scripts\activate
```

You'll know it's active when you see `(venv)` at the start of your terminal prompt.

## 4. Install Streamlit

```bash
pip install streamlit
```

## 5. Verify the installation

```bash
streamlit hello
```

This opens a demo app in your browser. If it loads, everything is working.

## 6. Create your app

Create a file called `app.py`:

```python
import streamlit as st

st.title("My first app")
st.write("Hello, world!")
```

## 7. Run your app

```bash
streamlit run app.py
```

Your app will open automatically at `http://localhost:8501`.

## Deactivate the environment

```bash
deactivate
```

---

## Project structure

```
my-app/
├── venv/
└── app.py
```
