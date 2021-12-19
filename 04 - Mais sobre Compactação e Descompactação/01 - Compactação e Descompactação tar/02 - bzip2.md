O comando **`tar`** não compacta, apenas empacota os arquivos. Podemos utilizá-lo em conjunto com outros compactadores. Compactar no formato **`.gz`**, é o formato gerado pelo compactador **`gzip`**.

Um outro formato de compactação que podemos utilizar junto com o **`tar`** é o formato **`.bzip2`**. Esse formato é mais eficiente na compactação, conseguindo criar arquivos menores. Porém o tempo que o **`.bzip2`** leva para criar o arquivo compactado é maior do que o tempo do **`gzip`**.

Para criar um arquivo **`.tar`** compactado com o **`bzip2`**, substituímos o **`-z`** (de **`gzip`**) por um **`-j`**. O formato que utilizamos é o **`.tar.bz2`**.

Aproveite e faça um teste:

**`$ tar -cjf work.tar.bz2 DIRETÓRIO`**

Você pode obter mais informações sobre o bzip2 na página do projeto: [http://www.bzip.org/](http://www.bzip.org/). Existe também um artigo na Wikipédia sobre o bzip2: [https://pt.wikipedia.org/wiki/Bzip2](https://pt.wikipedia.org/wiki/Bzip2).