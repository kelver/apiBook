# APIBook
## _API de cadastro de livros, baseada no interesse do usuário_
## Installation

Clone o repositório raíz,
```sh
git clone https://github.com/kelver/apiBook.git
```

Instale as dependências do projeto:

```sh
composer install
```
ao finalizar, copie o arquivo _.env.example_ e renomeie para _.env_ configurando os dados da sua conexão com o banco de dados e execute as migrações de banco de dados:
```sh
php artisan migrate
```
E as Seeders:
```sh
php artisan db:seed
```
Rode o comando para gerar a key secret do _JWT_
```sh
php artisan jwt:secret
```
De forma alternativa, existe liberada a rota _/register_ para cadastro de usuários.
Para acessar a documentação da API:
```sh
http://localhost/docs
```

## License

MIT
_______________
