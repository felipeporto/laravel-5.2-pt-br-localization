# Arquivos de linguagem do Laravel 5.2 - Português do Brasil

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/felipeporto/laravel-5.2-pt-br-localization.git ./pt-br
  ```
  
  Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -r pt-br/.git/
  ```
  
2. Configurar o Framework para utilizar a linguagem como Default
  ```
  // Linha 68 do arquivo config/app.php
  'locale' => 'pt-br',
  ```
