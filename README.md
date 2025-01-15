# Ransomware para sequestro de dados
 Situação: Concluído! 

Este é um projeto desenvolvido em Python com fins **estritamente educacionais**. O objetivo é aprender conceitos de criptografia e como proteger sistemas contra ataques.

## Descrição do Projeto
O projeto simula o funcionamento básico de um ransomware, permitindo criptografar e descriptografar arquivos de texto.
### Arquivos do Projeto

- **`encrypter.py`**: 
  - Este script é responsável por criptografar o conteúdo do arquivo de texto `teste.txt`.
  - Utiliza algoritmos de criptografia para embaralhar os dados e bloquear o acesso ao arquivo original.

- **`decrypter.py`**: 
  - Este script é usado para descriptografar o arquivo que foi criptografado pelo `encrypter.py`.
  - Restaura o conteúdo original do arquivo `teste.txt`.

- **`teste.txt`**:
  - Um arquivo de exemplo usado para testes de criptografia e descriptografia.

## Como Funciona
1. **Encriptação**:
   - Execute o script `encrypter.py`.
   - O conteúdo do arquivo `teste.txt` será criptografado e ficará inacessível sem a chave correta.

2. **Decriptação**:
   - Execute o script `decrypter.py`.
   - O conteúdo original do arquivo `teste.txt` será restaurado se a chave correta for usada.


