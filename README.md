# Repositório destinado a um crud api/rest utilizando PHP 8 sem framework.

Para contextualizar criaremos uma versão reduzida de um blog. A relação de usuários com posts será um para muitos. Não será implementado autenticação.

# Escopo

- Crud de usuários;
- Crud de posts;
- PSR's;
- Padrão RestFul;
- Validação de dados;
- Armazenamento de senha como hash no banco;
- Tratamento de exceções;
- Padronização em mensagens de commit;
- Testes.

# Modelagem

## 
Entidades

### User

- Id;
- Name: Obrigatório;
- E-mail: Obrigatório,Único;
- Password: Obrigatório.

### Post

- Id;
- Title: Obrigatório;
- Body: Obrigatório;
- UserId: Obrigatório.

### Endpoints

# Tecnologias utilizadas

- PHP 8.2;
- Composer 2.6.6;
- Xdebug;
- MySQL 8;
- Git;
- Docker;
- PHPCS;
- PHPCS Fixer;
- Pacotes:
    - PHP-DI;
    - PHPDOTENV;
    - PHPUNIT;
    - SWAGGER.