**
-Instalação do Django

No terminal execute:
pip install django

-Criando um projeto

Django oferece um comando para criação de projetos, no terminal use:

django-admin startproject seu projeto

Isso criara um diretório chamado seu projeto
Dentro dele tem um  arquivo chamado manage.py

-Estrutura do projeto:
**

<img width="405" height="140" alt="image" src="https://github.com/user-attachments/assets/b23f2292-0763-4bb0-a4bb-785ab07c4b92" />



## Descrição dos Arquivos

- manage.py  
Arquivo utilizado para executar comandos administrativos do Django.

- seu_projeto/  
Diretório principal do projeto.

- __init__.py  
Define o diretório como um pacote Python.

- settings.py  
Arquivo de configurações do projeto.

- urls.py  
Responsável pelo roteamento das URLs.

- asgi.py  
Configuração para servidores ASGI.

- wsgi.py  
Configuração para servidores WSGI.

## Executando o Servidor

Para iniciar o servidor de desenvolvimento, utilize:

python manage.py runserver

A aplicação ficará disponível em:
http://127.0.0.1:8000/
****


<img width="1354" height="968" alt="image" src="https://github.com/user-attachments/assets/22f785fb-0dd1-4e18-b4df-286ceac328b3" />

