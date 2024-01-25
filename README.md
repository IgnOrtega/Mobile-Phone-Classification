# Nota importante:  
Los proyectos de la carpeta ProyectosML fueron generados a partir de Python v3.10 y se utilizaron las librerias que están en el archivo MLrequirements.txt. Para ejecutar los códigos de la carpeta ProyectosML puede generar un entorno, a continuación se muestra como:  

Paso 1) Abrir una terminal, ya sea cmd, powershell:

Paso 2) Crear un entorno virtual en cierto lugar:  
```bash
python3.10 -m venv NombreEnv
```

Paso 3) Para cargar el entorno debe ejecutar el archivo activate que está en la siguiente dirección:
```bash
NombreEnv\Scripts\activate (cmd)
.\NombreEnv\Scripts\Activate (powershell)
.\ML\Scripts\Activate
```

Paso 4) Una vez cargardo el entorno debe instalar las librerias necesarias, estas están en el archivo MLrequirements.txt.
Para instalar las librerias del archivo MLrequirements.txt debe estar en el directorio del archivo y ejecutar:  
```bash
 pip install -r MLrequirements.txt
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
