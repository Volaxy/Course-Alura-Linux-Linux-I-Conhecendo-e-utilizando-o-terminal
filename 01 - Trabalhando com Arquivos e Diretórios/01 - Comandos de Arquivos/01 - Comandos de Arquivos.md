### Lista de Comandos
* `pwd`: É usado para ver o diretório atual.
* `ls`: Lista todos os diretórios dentro do diretório atual.
    * `ls -l`: Lista informações adicionais de cada diretório ou arquivo no local atual.
        * Ao executar este comando, uma série de informações aparece:
            * 1º - Lista de letras irá aparecer do lado esquerdo da tela, a letra *d*, significa se o arquivo é um diretório ou não.
            * 2º - O grupo e o usuário do dono do arquivo.
            * 3º - Tamanho do arquivo em *Bytes*.
            * 4º - Data de modificação do arquivo.
    * `ls -la`: Lista informações adicionais e arquivos invisíveis.
        * Arquivos invisíveis no Linux começam com um **`.`**
* `echo`: Repete uma sequência de caracteres depois do comando exibindo-os na tela.
    * `echo "ARGUMENTOS"`: Passa um argumento entre *"* para o comando `echo`.
    * `echo "ARGUMENTOS" > ARQUIVO`: Redireciona o argumento para um arquivo.
* `cat`: Lê o conteúdo de um arquivo.
* `clear`: Limpa a tela do console.
* `man COMANDO`: Mostra um manual de um comando especificado.
* `whoami`: Retorna o nome de usuário que está sendo usado.