## Proyecto de SITU

## _Requerimientos_

- Python 3.9.15
- Django==3.2.5
- Entorno virtual de python 


## _Implementación_
Se requiere descargar el repositorio en un directorio/carpeta y activar el entorno virtual de python.
Comandos
```sh
git clone https://github.com/fachamorro/ProyectoSITU.git
cd ProyectoSITU
source bin/activate
cd ProyectoTransporte
python3 manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
Verifique la implementación navegando a la dirección de su servidor web en el navegador preferido.

```sh
127.0.0.1:8000
```
## _Administración del aplicativo_

```sh
http://127.0.0.1:8000/admin/
usuario freddychamorro
contraseña 1234
```