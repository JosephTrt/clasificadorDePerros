# ClasificadorDePerros
Proyecto basado en la construcción de una red neuronal convolucional con el objetivo de clasificar e identificar dos perros de la raza Collie. Un macho tricolor, llamado Rex y una hembra dorada, llamada Ana.


## Installation
Crear un entorno virtual en la carpeta contenedora
```sh
python -m venv env
```
Activar el entorno
```sh
.\env\Scripts\activate
```
Instalar los los modulos y paquetes necesarios.

```sh
pip install -r requirements.txt
```

## Development
Descargar el set de datos del siguiente [ link](https://drive.google.com/file/d/1i28vqvt9sKgGS2W2A2ygGVwuVrJ1B3wl/view?usp=share_link)

Una vez descargado, abra el archivo titulado: ***clasificadorDePerros*** y copie la ruta del archivo zip en la seccion de acomodamineto del conjuto de datos:

```python
ruta_zip = 'path_to\data.zip'
```

Finalmente, seleccione la opcion **Run All** del jupyterNotebook