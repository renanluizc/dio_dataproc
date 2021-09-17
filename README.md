# Digital Innovation One

Código criado para utilização junto a plataforma da Digital Innovation One

## Desafio GCP Dataproc

O desafio faz parte do curso na plataforma da Digital Innovation One:

__*Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform*__

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

---

### Etapas do Desafio

1. Criar um bucket no Cloud Storage
2. Atualizar o arquivo ```contador.py``` com o nome do Bucket criado nas linhas que contém ```{SEU_BUCKET}```.
3. Fazer o upload dos arquivos ```contador.py``` e ```livro.txt``` para o bucket criado (instruções abaixo)
    - https://cloud.google.com/storage/docs/uploading-objects

4. Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando ```gs://{SEU_BUCKET}/contador.py```
5. O Job irá gerar uma pasta no bucket chamada ```resultado```. Dentro dessa pasta o arquivo ```part-00000``` irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.
6. 
