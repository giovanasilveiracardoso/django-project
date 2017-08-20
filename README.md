Url do projeto no pythonanywhere: http://giovanacardosoberti.pythonanywhere.com/

Instalação do projeto

1 Execute no terminal:
1.1 sudo apt-get install python3.6
1.2 git clone https://github.com/giovanasilveiracardoso/django-project.git
1.3 cd django-project
1.4 virtualenv --python=python3.6 myvenv
1.5 source myvenv/bin/activate
1.6 pip install -r requirements.txt

Banco de dados

1.7 Instale o PostgreSQL
1.8 Crie um banco de dados chamado 'teste'
1.9 Configure o usuário e senha da conexão em '/mysite/settings.py'
1.10 Execute no terminal: python manage.py migrate
1.11 Execute no terminal: python manage.py createsuperuser

Acessando o sistema

1.12 Execute no terminal: python manage.py runserver
1.13 Acesse http://127.0.0.1:8000/admin/
1.14 Utilize o usuário e senha definidos no 1.11 para acessar o sistema
