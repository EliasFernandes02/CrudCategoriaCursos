# CrudCategoriaCursos


## Requesitos necessários para executar o projeto:
Instalar o PHP versão ^7.4,
Instale o Mysql ou MariaDb versão 8.0,
instale o Composer 2.3.7

### Para baixar o projeto:
Crie uma pasta e abra ela no VScode.

Dentro da pasta, clone o projeto no terminal:
` git clone ...`
Dentro da pasta do projeto dê o seguinte comando no terminal:
`composer install`


## Criação do banco de dados:
Utilize os comandos SQL que estão no db.sql para a criação do banco de dados.

Lembre-se de criar primeiro a tb_categorias antes de tb_curso;

Para rodar o banco de dados no seu computador você precisa setar as variáveis em database.php 
no seu user em "DB_USER", nome do database "DB_NAME" e com sua senha pessoal em "DB_PASSWORD".

## Acesso ao projeto 
Abra o terminal na pasta principal do projeto e rode esse codigo:
`php -S localhost:3000 -t public` 

Para ter acesso a página de listar de cursos digite essa rota:

http://localhost:3000/cursos/listar

Depois disso utilize o menu para navegar em categorias




## Operações :
As operações estão bastante intuitivas, basta seguir os botões que estão na tela para fazer as operações.
