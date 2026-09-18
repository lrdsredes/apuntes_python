# Ficha de instalación Python + Jupyter + VS Code (Aula DAM/ASIR)

## Objetivo

Disponer de un entorno común para todos los usuarios del equipo que permita:

- Programar en Python desde línea de comandos.
- Crear y ejecutar scripts `.py`.
- Trabajar con notebooks `.ipynb`.
- Utilizar Visual Studio Code como entorno de desarrollo.
- Ejecutar programas relacionados con sistemas operativos, ficheros y administración de sistemas.
- Permitir el uso a alumnado sin privilegios de administrador.

---

# 1. Instalación de Python

## Descarga

Descargar Python desde:

https://www.python.org/downloads/

## Instalación

Ejecutar el instalador como administrador.

Marcar las opciones:

- Add Python to PATH
- Install for all users
- Use admin privileges when installing py.exe

Ruta recomendada:

```text
C:\Program Files\Python3XX
```

---

# 2. Verificación de Python

```bash
python --version
pip --version
```

---

# 3. Actualización de pip

```bash
python -m pip install --upgrade pip
```

---

# 4. Instalación de Jupyter

```bash
pip install notebook jupyterlab ipykernel
```

Comprobar:

```bash
jupyter lab
```

---

# 5. Librerías recomendadas

```bash
pip install psutil requests
```

---

# 6. Librerías incluidas en Python

```python
os
sys
pathlib
subprocess
shutil
glob
platform
socket
datetime
json
csv
sqlite3
tkinter
```

---

# 7. Instalación de Visual Studio Code

https://code.visualstudio.com/

Opciones recomendadas:

- Add to PATH
- Register Code as editor
- Open with Code
- Install for all users

---

# 8. Extensiones necesarias

Obligatorias:

- Python (Microsoft)
- Pylance (Microsoft)
- Jupyter (Microsoft)

Opcionales:

- GitLens
- Error Lens
- Black Formatter

---

# 9. Seleccionar intérprete Python

```text
Ctrl + Shift + P
Python: Select Interpreter
```

---

# 10. Prueba de funcionamiento

```python
import os

print('Hola DAM')
print(os.getcwd())
```

---

# 11. Prueba de Notebook

```python
import os
print(os.name)
```

---

# 12. Instalación recomendada de Git

https://git-scm.com/downloads

```bash
git --version
```

---

# 13. Comprobación desde una cuenta de alumno

```bash
python --version
pip --version
jupyter lab
```

---

# Configuración final recomendada

```text
Python
JupyterLab
Notebook
ipykernel
psutil
requests
Git
Visual Studio Code
```
