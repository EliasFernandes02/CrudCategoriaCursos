# CrudCategoriaCursos


### Requesitos necessários para executar o projeto:
Instalar o PHP versão ^7.4,
Instale o Mysql ou MariaDb versão 8.0,
instale o Composer 2.3.7

### Para iniciar o servidor:
Crie uma pasta e abra ela no VScode.

Dentro da pasta, clone o projeto no terminal:
` git clone ...`
Dentro da pasta do projeto dê os seguintes comandos no terminal:
`composer install`

`php -S localhost:3000 -t public` 

## Acesso ao projeto 
Para ter acesso a primeira página do projeto utilize a rota:

http://localhost:3000/cursos/listar

Depois disso utilize o menu para navegar em categorias



## Criação do banco de dados:
Utilize os comandos SQL que estão no db.sql para a criação do banco de dados.

Lembre-se de criar primeiro a tb_categorias antes de tb_curso;

Para rodar o banco de dados no seu computador você precisa setar as variáveis em conexao.php 
no seu host em "$dbhost", nome de usuario em "$dbusername" e com sua senha pessoal em "$dbpassword".

# Operações :
As operações estão bastante intuitivas, basta seguir os botões que estão na tela para fazer as operações.
