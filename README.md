# Apuntes de python

aclaración importante, para esté apunte estoy usando python 3 desde una distro de linux (MX Linux) basada en Debian.

## Usar comando `pip install` tiene algunos pasos extras
- Se necesita el paquete **venv**, en mi caso se instala con `sudo apt install python3-venv`
- Iniciar entorno virtual `python3 -m ven`
- Activar entorno `source .venv/bin/activate`
- ahora si, ejecutar `pip install <package-name>`

## Iniciar servidor con Flask 
para inciar servidor en vivo => `flask --app app.py --debug run`
