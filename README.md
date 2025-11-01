# Projeto Blog

Este é um projeto de um blog desenvolvido em Python (Django). O objetivo deste projeto é colocar em 
prática alguns conceitos do framework que venho estudando.

## Funcionalidades

- Personalização do blog via área administrativa do Django (título, descrição, links e páginas )
- Publicação, edição e exclusão de posts
- Busca e listagem de posts por tag, categoria e autor

## Tecnologias Utilizadas

- Python (Django) - backend
- Pillow - para redimencionar imagens dos posts
- django summernote - para criação e edição do conteúdo de posts e páginas (em forma de texto ou html)

## Instalação

1. Clone o repositório:
    ```bash
    git clone git@github.com:danniloraphael/projeto-blog.git
    ```
2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```
3. Faça as migrações:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```
4. Inicie o servidor:
    ```bash
    python manage.py runserver
    ```

## Uso

- Crie um superuser para acessar a área administrativa onde é possível fazer a criação
e gerenciamento de posts e personalização do blog.