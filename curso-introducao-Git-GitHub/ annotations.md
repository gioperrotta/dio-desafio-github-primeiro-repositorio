# Git  GitHub

Git é um software de versionamento de código distribuído, oferece suporte a criar e monitorar diferentes versões de arquivos

Git e Github são tecnologias diferentes porém complementares.

O Github é uma tecnologia usada para manutenção de arquivos e suas diferentes versões na nuvem

Benefícios de utilizar essas tecnologias:

- Controle de Versão
- Armazenamento em nuvem
- Trabalho em equipe
- Melhorar seu código
- Reconhecimento

### Comandos básicos do terminal

- Windows  / **Linux**
    - cls / **clear** - Limpa tela
    - cd / **cd** - muda de pasta
    - dir / **ls** - Lista o conteúdo de uma pasta
    - mkdir / **mkdir** - Cria uma pasta
    - mv nome Arq nome da pasta
    - del / rmdir - del exclui  arquivos no windows, rmdir *`nome da pasta` remove a pasta*
    - rm -rf  - remove a pasta e a f**lag -r** garante que todas as subpastas também serão removidas e a **flag -f** garante que nenhuma confirmação será solicitada

**SHA1** Algorítimo de encriptação (Algorítimo de HASH Seguro) gera chave de 40 dígitos.

## **Objetos básicos do Git**

- **BLOBS -** Contem metadados e o conteúdo do arquivo
- **TREES -** Contem um ou mais **BLOBS** ou seja armazenam **BLOBS,**
    
    **TREES** apontam para **BLOBS** ou outras **TREES**
    
- **COMMITS -** apontam para **TREE, PARENTE, AUTOR, MENSAGEM, TIMESTAMP**

todos esses objetos possuem em seu metadado um **SHA1** garantindo assim segurança e confiabilidade

## Primeiros Comandos git e github

- **git int**
- **git add**
- **git commit**
- **git config**
- **git status**
- **git log**
- **git remote add origin** `link copiado do github`
- **git remote -v**
- **git push origin master**

## Estado dos arquivos no repositório git

### Unttacked - não rastreáveis pelo git

### Tracked - rastreáveis pelo git

- **Unmodified** - Usar qualquer editor para o estado de Modified
- **Modified** - Usar o comando git Add  <File Name> para o estado Staged
- **Staged** - Usar o comando git commit para o estado Unmodified