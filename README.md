# Installation

1. Create a virtual environment:

**Linux:**
```bash
virtualenv -p python3 venv && cd venv && source bin/activate
```

**Windows:**
```batch
python -m venv venv && venv\Scripts\activate.bat
```

2. Activate the virtual environment:

**Linux:**
```bash
cd venv && source bin/activate
```

**Windows:**
```batch
.\venv\Scripts\activate
```

3. Install requirements:

```batch
pip install -r requirements.txt
```

4. Run JupterLab or Jupyter Notebook:

**JupyterLab:**
```batch
jupyter lab
```

**JupyterNotebook:**
```batch
jupyter notebook
```