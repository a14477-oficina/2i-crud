# 2i-crud

# INTRUDUÇÃO
Este projeto apresenta um sistema CRUD que permite Criar, ler, atualizar e eleminar produtos de umka base de dados MySql.

# Tecnologias Utilizadas

PHP 7+

MySQL

Bootstrap 5

HTML, CSS e JavaScript

# Funcionalidades

O sistema permite:

Criar novos registros no banco de dados.

Consultar e visualizar dados armazenados.

Editar e atualizar informações.

Excluir registros de forma segura.

# Requisitos

Para executar este projeto, você precisará de:

Uma conta em um serviço de hospedagem compatível com PHP e MySQL.

Acesso a um gerenciador de banco de dados, como phpMyAdmin.

Um navegador web para acessar a aplicação.

# Instalação e Configuração

Clone este repositório para seu ambiente:

git clone https://github.com/seu-usuario/seu-repositorio.git

Configure o banco de dados:

Acesse o painel de administração do seu servidor de hospedagem.

Crie um banco de dados e um usuário com as permissões necessárias.

Importe o arquivo database.sql para estruturar as tabelas.

Ajuste as credenciais de conexão no arquivo config.php.

Faça o upload dos arquivos para o servidor utilizando um cliente FTP ou o gerenciador de arquivos da hospedagem.

Acesse o sistema pelo navegador:

http://seu-dominio.com/seu-projeto/

# Estrutura do Projeto

A organização dos arquivos é a seguinte:

/seu-projeto
├── index.php       # Página inicial
├── create.php      # Página de criação de registros
├── read.php        # Página de leitura de registros
├── update.php      # Página de atualização de registros
├── delete.php      # Página de exclusão de registros
├── config.php      # Configuração do banco de dados
├── database.sql    # Estrutura do banco de dados
└── assets/         # Arquivos CSS, JS e imagens

# Como Contribuir

Faça um fork deste repositório.

Crie uma nova branch para suas alterações (git checkout -b minha-feature).

Realize suas modificações e faça um commit (git commit -m 'Descrição da alteração').

Envie as mudanças para o GitHub (git push origin minha-feature).

Abra um Pull Request para análise.
