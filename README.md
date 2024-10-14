### php_oo_project
PHP orientado a objetos
### CLONANDO O PROJETO

    $ sudo git clone --branch dev-master https://github.com/fsphpdeveloper/php_oo_project.git.

### ESTRUTURA DO DIRETÓRIO `www` APÓS O CLONE DO PROJETO
    .
    ├── drwxr-xr-x 2 root root 4096 May 13 09:09 html
    ├── drwxr-xr-x 4 root root 4096 Oct 14 17:12 php_oo_project
    └── drwxr-xr-x 9 dev dev  4096 Oct 14 01:37 phpoo
Observe que root é o proprietário do diretório `php_oo_project`.

### ATRIBUINDO PERMISSÃO DE LEITURA E ESCRITA 
      
    $ sudo chown -R $USER:$USER /var/www/php_oo_project
### AGORA TEMOS:
        .
    ├── drwxr-xr-x 2 root root 4096 May 13 09:09 html
    ├── drwxr-xr-x 4 dev dev 4096 Oct 14 17:12 php_oo_project
    └── drwxr-xr-x 9 dev dev  4096 Oct 14 01:37 phpoo
### INICIANDO COM O COMPOSER   
  
    $ composer init
    $ composer update
Lembre-se, o composer oferece restrição ao root, por questóes de segurança.

### EDITANDO COM O VSCODE
    $ code .

    