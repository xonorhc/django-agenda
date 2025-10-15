# django-agenda

Iniciar o projeto Django

```bash
python -m venv venv
source ./venv/bin/activate
pip install django
django-admin startproject project .
python manage.py startapp contact
```

Configurar o Git

```bash
git config --global user.name 'YOUR_NAME'
git config --global user.email 'YOUR_EMAIL@EMAIL.COM'
git config --global init.defaultBranch main
git init
git add .
git commit -m 'MENSAGE'
git remote add origin URL
```

Migrando a base de dados do Django

```bash
python manage.py makemigrations
python manage.py migrate
```

Criando e modificando a senha de um superusuario Django

```bash
python manage.py createsuperuser
python manage.py changepassword USER_NAME
```
