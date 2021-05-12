
* ## Docs
  ### *Django*
  https://www.djangoproject.com/
  <br>

  ### *Django Rest Framework*
  https://www.django-rest-framework.org/
* ## Virtual Environments
  ### *Criando um virtual environment*
  `$ python3 -m venv ./{nome da pasta do projeto}`

  ### *Ativando environment*
  `$ source venv/bin/activate`
  <br>

* ## Instalação dos Pacotes
  ### *Instalando o Django*
  `$ pip install Django`

  ### *Visualizar os pacotes instalados*
  `$ pip freeze`
  
  ### *Instalando o Django Rest Framework*
  `$ pip install djangorestframework`
  <br>

* ## Migrations
  ### *Criando uma migração*
  `$ python manage.py makemigrations`
  <br>
  ### *Aplicando uma migração*
  `$ python manage.py migrate`
* ## Comandos
  ### *Criando um novo projeto*
  `$ django-admin startproject {nome da pasta do projeto} .`
  <br>
  ### Iniciando servidor
  `$ python manage.py runserver`
  <br>
  ### Criando uma nova API
  `$ python manage.py startapp {nome da API}`
  <br>
  ### Criando um super user
  `$python manage.py createsuperuser`