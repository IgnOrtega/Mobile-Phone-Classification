# Acerca del proyecto:  
Este proyecto consiste en clasificar un celular en el intervalo de precio correspondiente. Para resolver este problema se tienen los datos que caracterizan a los teléfonos móviles como:  
- la energía de la batería,  
- las especificaciones de la cámara,  
- el soporte de red,  
- la memoria,  
- las dimensiones de la pantalla,  
- obviamente los intervalos de los precios y otros atributos.

Para este problema se hicieron estudios de los datos, se eliminaron "variables independientes" que no explicaban la variable dependiente y se aplicaron distintos métodos de machine learning.  

Fuente data:  
https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification

# Nota importante:  
Este proyecto fue generado a partir de Python v3.11 y se utilizaron las librerias que están en el archivo last_requirements.txt. Para el código del proyecto se debe generar un entorno, a continuación se muestra como:  

Paso 1) Abrir una terminal (powershell):

Paso 2) Crear un entorno virtual en cierto lugar:  
```bash
python3.11 -m venv NombreEnv
```

Paso 3) Para cargar el entorno debe ejecutar el archivo activate que está en la siguiente dirección:
```bash
.\NombreEnv\Scripts\Activate
```

Paso 4) Una vez cargardo el entorno debe instalar las librerias necesarias, estas están en el archivo last_requirements.txt.
Para instalar las librerias del archivo last_requirements.txt debe estar en el directorio del archivo y ejecutar:  
```bash
 pip install -r last_requirements.txt
```

Paso 5) Para que el sistema reconozca el kernel creado debe ejecutar los siguientes comandos:  
```bash
pip install ipykernel
python -m ipykernel install --user --name=NombreEnv
```

Paso 6) Luego, puede ejecutar jupyter notebook y listo.
```bash
 jupyter notebook
```
