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


# DJANGO

## Instalação do Django

No terminal, execute o seguinte comando para instalar o Django:

pip install django

---

## Criação de um Projeto

O Django oferece um comando próprio para a criação de projetos.  
No terminal, utilize:

django-admin startproject seu_projeto

Esse comando criará um diretório chamado **seu_projeto**.

Dentro desse diretório há um arquivo chamado **manage.py**, responsável por gerenciar comandos do projeto.

---

## Estrutura do Projeto

A estrutura inicial do projeto Django contém os seguintes arquivos:

- **manage.py**  
  Arquivo localizado no diretório raiz do projeto. Permite executar diversos comandos administrativos, como migrações do banco de dados, execução de testes e inicialização do servidor.

- **settings.py**  
  Contém as configurações do projeto, como banco de dados, aplicativos instalados, middlewares e caminhos para arquivos estáticos.

- **urls.py**  
  Responsável por mapear as URLs para as funções ou views que irão manipular as requisições.

- **wsgi.py**  
  Utilizado para iniciar o servidor no padrão WSGI.

- **asgi.py**  
  Utilizado para iniciar o servidor no padrão ASGI.

---

## Executando o Servidor Local

No terminal, execute:

python manage.py runserver

O servidor será iniciado na porta padrão **8000**.

Resultado esperado:

Starting development server at http://127.0.0.1:8000/  
Quit the server with CONTROL-C.

---

## Migrações

As migrações permitem gerenciar o estado do banco de dados sem a necessidade de escrever SQL manualmente.

Para criar e aplicar as migrações, execute no terminal:

python manage.py makemigrations  
python manage.py migrate

Esses comandos criam as migrações do sistema e aplicam automaticamente as alterações no banco de dados.

---

## Criar Superusuário (Admin do Django)

Para criar um usuário administrador do Django, execute:

python manage.py createsuperuser

---

## Executar Testes

Para rodar os testes do projeto, utilize:

python manage.py test

