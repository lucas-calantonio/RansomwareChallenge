# 🔐 RansomwareChallenge

Neste projeto, vamos aprender a **encriptografar** e **descriptografar** arquivos utilizando as bibliotecas `os` e `pyaes` no Linux. A seguir, confira o passo a passo para reproduzir o funcionamento do projeto:

---

## 🛠️ Preparação  

1. Certifique-se de que os arquivos `encrypter.py` e `decrypter.py` estão disponíveis.  
2. Navegue até o diretório onde estão armazenados. Por exemplo:
```bash
   cd /kali/usuario_lucas/documentos/RansomwareChallenge
```

## 📄 Criar um arquivo para teste

1. Crie um arquivo chamado `teste.txt` usando o editor de texto `nano`
  ```bash
nano teste.txt
```
2. Escreva algo no arquivo, como um texto simples.
3. Salve e saia do editor:
`Ctrl + O (salvar)`
`Enter (confirmar o nome do arquivo)`
`Ctrl + X (sair do editor).`

## 🔒 Encriptografar o arquivo

1. Execute o script de encriptação:
```bash
python encrypter.py
```
2. Verifique os arquivos no diretório com o comando `ls`.
3. Um novo arquivo será gerado: `teste.txt.ransomwaretroll`.
**Ao abrir este arquivo, você verá que os dados não estão mais legíveis – eles foram encriptografados.**

![Captura de tela 2024-12-18 173235](https://github.com/user-attachments/assets/02d36987-6649-4a6d-ba65-61c1612f28e7)

## 🔓 Descriptografar o arquivo

1. Para reverter o processo e tornar o arquivo legível novamente, execute:
```bash
python decrypter.py
```
2. Verifique os arquivos no diretório novamente com `ls`.
O arquivo original, `teste.txt`, estará disponível e legível.

![Captura de tela 2024-12-18 173411](https://github.com/user-attachments/assets/1863fda1-a964-4e41-b1ca-458869b9a3b4)

## 🚀 Conclusão

Este projeto é uma introdução prática à manipulação de arquivos utilizando encriptação e decriptação no Linux, demonstrando conceitos fundamentais em cybersecurity.
