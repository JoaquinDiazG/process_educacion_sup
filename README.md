## Paso1: Redirigete a la carpeta del proyecto

## Paso 2: Cree el ambiente virtual
python -m venv myenv

## Paso 3: Activar el entorno virtual
myenv\Scripts\activate

### Observacion: si está en MacOs o Linux debe usar:
source myenv/bin/activate

## Paso 4: Instalar las librerias del archivo requirements.txt
pip install -r requirements.txt

## Paso 5: Luego descargar el csv mas reciente de la siguiente url:
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: Ejectuar la aplicacion
python get_excel_resumen_es.py