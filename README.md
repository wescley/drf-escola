# 1. drf-escola
Exemplo de uso do django rest framework em um app de escola

# 2. Principais comandos
## 2.1. Cria uma máquina virtual python
```
python -m venv ./venv
```

## 2.2. Inicia a máquina virtual python
```
venv\Scripts\activate.bat
```

## 2.3. Instala o django e o django rest framework
```
pip install django, djangorestframework, markdown django-filter
```

## 2.4. Iniciando o servidor
```
python manage.py runserver
```

## 2.5. Criar um projeto
```
django-admin startproject escola
```

## 2.6. Cria as tabelas do banco de dados
```
python manage.py makemigrations
python manage.py migrate
```

## 2.7. Cria o super usuário
```
python manage.py createsuperuser
```
