# PHP CS Fixer Config

## Realize a instalação (local) recomendada:
Dentro da pasta do projeto, execute os seguintes comandos:

```sheel
mkdir --parents tools/php-cs-fixer
composer require --working-dir=tools/php-cs-fixer friendsofphp/php-cs-fixer
```
## Colocar um script para execução no composer
Dentro do composer.json e em "scripts"
```
"nome-do-script": [
    "@php tools/php-cs-fixer/vendor/bin/php-cs-fixer fix"
]
```
