Url do projeto no pythonanywhere: http://giovanacardosoberti.pythonanywhere.com/

#### Instalação do projeto

```sh
$ sudo apt-get install python3.6
$ git clone https://github.com/giovanasilveiracardoso/django-project.git
$ cd django-project
$ virtualenv --python=python3.6 myvenv
$ source myvenv/bin/activate
$ pip install -r requirements.txt
```

#### Banco de dados

Instale o PostgreSQL
Crie um banco de dados chamado 'teste'
Configure o usuário e senha da conexão em '/mysite/settings.py'
```sh
$ python manage.py migrate
$ python manage.py createsuperuser
```

#### Acessando o sistema

```sh
$ python manage.py runserver
```
Acesse http://127.0.0.1:8000/admin/
Utilize o usuário e senha definidos acima para acessar o sistema
