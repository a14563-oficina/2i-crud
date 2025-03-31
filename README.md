# a14563 Crud

Este projeto é um sistema CRUD (Create, Read, Update, Delete) desenvolvido em PHP. Ele permite gerenciar produtos em uma base de dados, incluindo a adição, edição e eliminação de itens.

# Requisitos

Antes de iniciar, certifique-se de que seu ambiente atenda aos seguintes requisitos:
- Hospedagem com suporte a PHP (cPanel foi o utilizado)
- PHP 7.4 ou superior
- PhpMyAdmin (para gerenciar a base de dados)

# Instalação no cPanel

1. Acessa o cPanel.
   **http://cpanel.alojamento-gratis.com/**
   
3. No **Online File Manager**, envia os arquivos do projeto para a pasta `htdocs` ou outra pasta desejada.
4. Configure a base de dados:
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

- A página de principal permite ver, adicionar, editar e eliminar produtos.
- As imagens dos produtos devem ser adicionadas na pasta `images/`.
- O estilo da aplicação pode ser personalizado no arquivo `css/style.css`.

## Autor

Desenvolvido por Rodrigo Ferreira.
