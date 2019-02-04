# Serverless-Web-App
Serverless Web Application using AWS 

## Inicio

* Instalar virtualenv

´´´console
pip install virtualenv
´´´ 

* Modificar Archivo *run-init.bat*, ya que hay que cambiar la ruta del ejecutor de Python3.6 de la maquina.
* Ejecutar *run-init.bat* que hara lo siguiente:
	* Creara el ambiente virtual.
	* Activara el nuevo ambiente.
	* Instalara las librerias requeridas

* Crear la carpeta *.aws*, la el archivo *credentials*, con el siguiente contenido:
'''python
aws_access_key_id = '<Creada en su cuenta AWS>'
aws_secret_access_key = '<Creada en su cuenta AWS>'
'''
