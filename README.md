# First Django App

## Case 1: Take the tutorial 

### Directory
Crating the directory:
`mkdir first-django-app`
Moving to directory:
`cd first-django-app`.

### Environment 
Adding the enviroment:
`python3 -m venv env`
Activation:
`source env/bin/activate`.

### Django Project
Install Django:
`pip install Django`.\
Start project:
`django-admin startproject mysite .`. 

### Run server
`python manage.py runserver`
Congratulations! We start working

## Case 2: Clone the repository

### Clone the repository
`git clone https://github.com/FrancoZurschmitten/first-django-app.git`
`cd frist-django-app`

### Environment
Adding and install dependecies:
`
python -m venv env
pip install requirements.txt
`

### Migrations
Applying migrations
`
./manage.py makemigrations
./manage.py migrate 
`

### Run server
`./manage.py runserver`

## Tips
For the **Error: That port is already in use.**
`
sudo fuser -k 8000/tcp
`

# Para los que son de Boca

## Caso 1: Hacer el tutorial

### Directory
Creamos el directoria que va a contener nuestro projecto:
`mkdir first-django-app`
Posteriormente, nos movemos a la carpeta:
`cd first-django-app`.

### Entorno
Creamos un entorno dentro del directorio:
`python3 -m venv env`
Lo activamos:
`source env/bin/activate`.

### Django Project
Instalamos Django:
`pip install Django`.\
Luego, creamos el projecto dentro del directorio:
`django-admin startproject mysite .`. 
El punto al final es para que genere los archivos dentro de el directorio actual.

### Run server
Para iniciar nuestro servidor:
`python manage.py runserver`
Felicidades! Y ahora solo queda empezar a hacer el tutorial.

## Caso 2: Clonar el repositorio

### Clonar el repositorio
Pega esto en tu terminal:
`git clone https://github.com/FrancoZurschmitten/first-django-app.git`
Muevete al repositorio:
`cd frist-django-app`

### Entorno
Creamos un entorno e installamos dependencias:
`
python -m venv env
pip install requirements.txt
`

### Migraciones
Applica las migraciones:
`
./manage.py makemigrations
./manage.py migrate 
`

### Run server
Inicia el Servidor
`./manage.py runserver`

Instalar dependencias:


## Tips
Para el **Error: That port is already in use.**
`
sudo fuser -k 8000/tcp
`