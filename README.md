# Fundamentos de la Computación Cuántica

En este repositorio compartiré mis resoluciones de los prácticos de la materia optativa Fundamentos de la Programación Cuántica.

## Pasos de Ejecución

Instalación del creador de entornos virtuales en Python:

```sh
sudo apt install python3.13-venv
```

Creación del ambiente:

```sh
python -m venv venv
```

Si usa `python 3`, utilice `python3` en su lugar.

Activación del ambiente:

```sh
source venv/bin/activate
```

Instalación de los requerimientos:

```sh
pip install -r requirements.txt
```

Si utiliza python3, utilice `pip3` en lugar de `pip`.

Realizados todos los pasos anteriores, ya puede ejecutar la _notebook_.

Para desactivar el ambiente:

```sh
deactivate
```

Para borrarlo, una vez desactiva, utilice:

```sh
rm -rf venv
```

Instalación de los requisitos:

python3 -m venv venv
source venv/bin/activate
pip install jupyter
pip install qiskit_aer
pip install qiskit[visualization]
