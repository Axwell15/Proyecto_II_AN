
# Requisitos para ejecutar el proyecto

Este proyecto requiere las siguientes librerías de Python:

```bash
pip install numpy matplotlib notebook
```

También se necesita tener instalado **ffmpeg** para poder exportar la animación en formato MP4.

## Instalación de ffmpeg

- En Ubuntu/Debian:

```bash
sudo apt install ffmpeg
```

- En Windows:

1. Descarga desde: https://ffmpeg.org/download.html  
2. Extrae el archivo ZIP  
3. Agrega la carpeta `bin/` a la variable de entorno `PATH`

Una vez instaladas las librerías y ffmpeg, puedes ejecutar el archivo:

```bash
python simulacion_lorenz.py
```

Se generará automáticamente una carpeta `resultados/` con todas las gráficas.
Se generará el archivo `atractor_lorenz.mp4`.
