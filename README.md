# Test Ecommerce

Este é um sistema de gerenciamento de loja criado com Django que permite o cadastro de clientes, funcionários, produtos e o registro de vendas. O projeto utiliza Django REST Framework para a criação de APIs e Django Filters para facilitar a filtragem de dados.

## Funcionalidades

- **Cadastro de clientes**: Gerencie informações dos clientes, como nome, e-mail, telefone, etc.
- **Cadastro de funcionários**: Adicione, edite e remova funcionários da loja.
- **Cadastro de produtos**: Gerencie o catálogo de produtos da loja, incluindo nome, descrição, preço e estoque.
- **Registro de vendas**: Registre e acompanhe as vendas realizadas na loja, associando clientes, produtos e funcionários responsáveis.

## Tecnologias Utilizadas

- **Django**: Framework web utilizado para a criação da aplicação.
- **Django REST Framework**: Biblioteca utilizada para criação das APIs REST.
- **Django Filters**: Ferramenta para facilitar a filtragem de dados nas APIs.
- **SQLite**: Banco de dados padrão utilizado para armazenar os dados.

## Instalação

### 1. Clone o repositório

bash
git clone https://github.com/seu_usuario/django-store-management.git
cd django-store-management


### 2. Crie um ambiente virtual

bash
python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate


### 3. Instale as dependências

bash
pip install -r requirements.txt


### 4. Realize as migrações do banco de dados

bash
python manage.py migrate


### 5. Crie um superusuário para acessar o painel de administração

bash
python manage.py createsuperuser


### 6. Inicie o servidor

bash
python manage.py runserver


Agora você pode acessar o projeto em http://127.0.0.1:8000/ e o painel de administração em http://127.0.0.1:8000/admin/.


mude o nome para Test-Ecommerce
