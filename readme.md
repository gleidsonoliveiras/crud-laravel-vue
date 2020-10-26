

# Projeto Prático de Laravel + JWT + Vue JS + Axios + Vuex + VueRouter + Boas Práticas

> Exemplo básico Laravel com Vue JS

## Baixar o projeto
Primeiro passo, clonar o projeto:
``` bash
# Clonar
git clone https://github.com/gleidsonoliveiras/crud-laravel-vue.gitt

# Acessar
cd laravel-com-vue-exemplo
```

## Configuração - Backend

``` bash
# Instalar dependências do projeto
composer install

# Configurar variáveis de ambiente
cp .env.example .env
php artisan key:generate

# Configuração do JWT
php artisan jwt:secret

# Criar migrations (tabelas e Seeders)
php artisan migrate --seed

# Criar link simbólico storage/app/public para public/storage/
php artisan storage:link
```

## Login
O usuário de teste é:
```
email:    gleidson.oliveiras@gmail.com
password: 123456
```

## Configuração - Frontend
``` bash
# Atualizar dependências
npm install

# Rodar em ambiente local localhost:8080
npm run dev

# Rodar em ambiente de produção
npm run build
```
