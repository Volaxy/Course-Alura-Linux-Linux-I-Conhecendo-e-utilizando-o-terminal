Podemos obter ajuda na documentação do Linux, as man pages, através do comando **`man`**. Uma outra forma de obter ajuda sobre a utilização do comando, de uma forma mais resumida, é utilizando o parâmetro **`--help`** suportado por alguns comandos, ou utilizando o comando **`help`**.

O **`help`** é um comando interno do interpretador **`bash`**, que, quando executado sem parâmetros, retorna uma lista com todos os demais comandos internos do shell **`bash`**. Quando executado com parâmetro, o comando **`help`** retorna a sintaxe de utilização e uma descrição do comando interno que estamos interessados.
```
$ help pwd
$ date --help
```
Quando fazemos **`date --help`**, encontramos, dentre outras coisas, ajuda sobre como formatar a nossa data. Podemos imprimir, por exemplo, a data no formato **`dia/mes/ano`**:
```
$ date "+%d/%m/%Y"
23/01/2016
```

Sempre que precisar consultar os parâmetros que um comando suporta, você pode pedir ajuda através do **`help`** ou **`--help`**.