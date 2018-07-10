# Projeto treinamento back-end -- SmartNX

##### Problema:
Desenvolver um sistema de cadastro de posts que podem ser filtrados por categoria, onde deve conter um CRUD para os posts.
As categorias são: WhatsApp, Messenger, SmartNX

Obs: As categorias não precisam de CRUD.

**Entidades:**
- Post
    - id , titulo , conteudo , autor(string) , id_categoria , created_at , updated_at

**Obs:** Os campos 'created_at' e 'updated_at', são criado automaticamente através das migrations do laravel.

**Itens que serão avaliados:**
- utilização das PSR's do PHP
- utilização do Repository ou qualquer outra prática que siga o conceito de programação DRY
- utilização dos padrões do laravel versão 5.4 para desenvolver um CRUD
- criatividade na construção do back-end do sistema

---
#### Porque da utilização do Repository

Ao criar novas consultas utilizando o design pattern **Repository**, facilita a manutenabilidade do código e a reutilização de código seguindo o conceito da programação DRY (don't repeat yorself).


##### Links de auxílio:
- PSR-1 - https://www.php-fig.org/psr/psr-1/
- PSR-2 - https://www.php-fig.org/psr/psr-2/
- Design Pattern Repository - https://medium.com/by-vinicius-reis/repository-pattern-n%C3%A3o-precisa-ser-chato-principalmente-com-laravel-d97235b31c7e
---
