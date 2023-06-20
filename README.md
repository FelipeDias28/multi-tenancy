1 Tenant (Empresa) Pode ter vários Usuários vinculados.

Comando para criar model e migration:
php artisan make:model Models\Tenant -m

Como mexemos na ordem das migrations foi preciso rodar o seguinte comando:
composer dump-autoload