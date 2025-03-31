# a14563 Crud

Este projeto é um sistema CRUD (Create, Read, Update, Delete) desenvolvido em PHP. Ele permite gerir produtos numa base de dados, incluindo a adição, edição, atualização e eliminação de itens.

## Requisitos

Antes de iniciar, certifica-te de que o teu ambiente atende aos seguintes requisitos:
- Alojamento com suporte a PHP
- PHP 7.4 ou superior
- PhpMyAdmin (para gerir a base de dados)

## Instalação no cPanel

1. Acessa o cPanel.
   **http://cpanel.alojamento-gratis.com/**
   
3. No **Online File Manager**, envia os arquivos do projeto para a pasta `htdocs` ou outra pasta desejada.
4. Configura a base de dados:
   - No cPanel, vai até **phpMyAdmin** e cria uma nova base de dados.
   - Importa o arquivo **products.sql**.
5. Configura a conexão com a base de dados:
   - Edita o arquivo **config.php** e insere as tuas credenciais:
   
    $conn = mysqli_connect('Sql_host_name','Sql_user_name','password','Sql_db_name');

6. Acesse o sistema pelo navegador:
   ```
   https://teudominio.com/admin_page.php
   ```

## Como Usar

- A página principal permite ver, adicionar, editar e eliminar produtos.
- As imagens que são adicionadas no site, são enviadas para a pasta `images/`.
- O estilo da aplicação pode ser personalizado no arquivo `css/style.css`.

## Autor

Desenvolvido por Rodrigo Ferreira.
