# Introdução ao Git e ao GitHub

## **Introdução ao Git**
### Entendendo o que é o Git e sua importância
- Software de versionamento de código
1. Controle de versão
2. Armazenamento
3. Trabalho em equipe
4. Melhorar seu código
5. Reconhecimento

## **Navegação via command line interface e instalação**
- Comandos básicos para um bom desempenho no terminal:
    - cd (abre pasta)
    - cd .. (retrocede pasta)
    - dir (listar diretório)
    - mkdir (criar uma pasta)
    - cls (limpar a tela)
    - echo (criar arquivo)
    - del (deletar arquivo)
    - rmdir (deletar pasta)

## **Entendento como o Git funciona por baixo dos panos**
- SHA 1: Secure Hash Algorithm, é um conjunto de funções hash criptográficas projetadas pela NSA. Algoritmo de encriptação. Gera um conjunto de caracteres identificador de 40 dígitos. É uma forma curta de apresentar um arquivo.
- Objetos internos do Git:
    - Blob: os arquivos ficam guardados dentro desse objeto, que contém metadados. 
    - Tree: armazena blobs. Pode conter outras trees.
    - Commit: objeto que junta tudo, que dá sentido para a alteração feita. Aponta para uma árvore, para um parente (último commit realizado antes dele), aponta para um autor, aponta para uma mensagem e contém um timestamp.

## **Ciclo de vida dos arquivos Git**
- Git init (inicializa repositório dentro do diretório)
- Tracked (git já tem ciência desses arquivos)
- Untracked (git ainda não tem ciência desses arquivos)
- Git status (mostra estado dos arquivos)

### Comandos
- git init (iniciar o git)
- ls (listar)
- ls -a (mostrar arquivos ocultos) 
- git add
- git commit
- git clone (clonar repositório GitHub)
- git add . (adicionar todos os arquivos)
- git commit -m "" (commit com mensagem entre aspas)
- git push origin main (enviar todos os commits para a nuvem)