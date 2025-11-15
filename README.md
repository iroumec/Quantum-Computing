# Introducción a la Computación Cuántica

Este repositorio compartiré mis resoluciones de los prácticos de la materia optativa Introducción a la Programación Cuántica.

## Comandos

sudo apt install python3.13-venv
python3 -m venv venv
source venv/bin/activate
pip install qiskit
pip install qiskit_aer
pip install jupyter
pip install pillow

Verificación de la versiín de pillow:

```sh
python -c "import PIL; print(PIL.__version__)"
```

Instalación de qiskit con todo lo necesario para visualización:

```sh
pip install qiskit[visualization]
```

Dentro del ambiente:
deactivate

Fuera de este:
rm -rf venv
