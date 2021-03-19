# Clima Local

Version 1.0.0

Sistema usando django e react junto com a a api openweathermap.


---

##Instalação

- npm install
- criar bando de dados postgres local e adicionar configurações no settings.py:

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'previsaoDB',
        'USER': 'postgres',
        'PASSWORD': 'root',
        'HOST': 'localhost'
    }
}

- python manage.py migrate
- no repósitorio previsao-front executar npm start para rodar servidor local
- executar python manage.py para rodar servidor local do django

---

##Fluxo do sistema

- pesquisar cidades na página inicial com a openweatherAPI
- o nome deve ser válido
- adicionar pesquisa no banco de dados
- em "listar registros" verificar pesquisas criadas

---

## Licence & copyright

&copy; Henrique Duarte Leite
