# Entendendo um Ransomware na Prática com Python

#### Desafio de projeto do Bootcamp Cibersegurança #2, pela DIO.

## Bibliotecas

- os
- pyaes
- sys

## Comandos do programa

Ambos são feitos para serem executados via CLI e de forma bem semelhante

### Objetivos:
  - Utilizar um código em Python para criptografar um arquivo de texto e outro código para descriptografá-lo, voltando a ser como o original;
  - Relacionar aos conteúdos estudados durante o Bootcamp, como criptografia, vulnerabilidades, ataques cibernéticos e ransomwares, por exemplo.

---

### Estrutura:
  - **encrypter.py**
    - Código para pegar o arquivo de teste e criptografá-lo.

  - **decrypter.py**
    - Código para descriptografar o arquivo já criptografado.

  - **teste.txt**
    - Arquivo de texto que será usado para as demonstrações, sendo criptografado e descriptografado em seguida.

---


### Encrypter

Comando:
python3 encrypter.py {nome-do-arquivo-para-criptografar} {chave-de-16-24-ou-32-bytes-para-criptografar}

### Decrypter

Comando:
python3 encrypter.py {nome-do-arquivo-para-criptografar} {chave-de-16-24-ou-32-bytes-para-criptografar}

