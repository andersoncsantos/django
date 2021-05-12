
* ## Docs
  ### *Django*
  https://www.djangoproject.com/
  <br>

  ### *Django Rest Framework*
  https://www.django-rest-framework.org/
* ## Virtual Environments
  ### *Criando um virtual environment*
  ```bash
  $ python3 -m venv ./{nome da pasta do projeto}
  ```
  <br>

  ### *Ativando environment*
  ```bash
  $ source venv/bin/activate
  ```
* ## Instalação dos Pacotes
  ### *Instalando o Django*
  ```bash
  $ pip install Django
  ```
  <br>
	
  ### *Visualizar os pacotes instalados*
  ```bash
  $ pip freeze
  ```
  <br>

  ### *Instalando o Django Rest Framework*
  ```bash
  $ pip install djangorestframework
  ```
* ## Migrations
  ### *Criando uma migração*
  ```bash
  $ python manage.py makemigrations
  ```
  <br>

  ### *Aplicando uma migração*
  ```bash
  $ python manage.py migrate
  ```
* ## Comandos
  ### *Criando um novo projeto*
  ```bash
  $ django-admin startproject {nome da pasta do projeto} .
  ```
  <br>

  ### Iniciando servidor
  ```bash
  $ python manage.py runserver
  ```
  <br>

  ### Criando uma nova API
  ```bash
  $ python manage.py startapp {nome da API}
  ```
  <br>

  ### Criando um super user
  ```bash
  $ python manage.py createsuperuser
  ```