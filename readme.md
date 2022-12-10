# Tech4me

## Carreira Frontend

### Turma Itaú

Alguns comandos de GIT:

Sempre em minúsculas, para não gerar um 'erro fatal'
git clone <url>

warning: You appear to have cloned an empty repository.
está vazio mesmo!

Agora nossa pasta está sob controle de versionamento

- fatal: not a git repository
  - significa que a pasta não está versionada
- cd _sua pasta_

  - para navegar até a pasta

- main

  - significa **principal**

- git status

  - permite ver o status da pasta versionada
    - Se houve modificação e se o git sabe da existência dessas modificações.

- Uncontrolled/Untracked

  - Está na pasta versionada, mas o git ainda não o conhece

- git add nome_arquivo

  - adiciona o arquivo ao controle de versionamento

- git add nome1 nome2

  - vários arquivos separados com espaço

- Incluir aspas em nomes de arquivo com espaços

- git add \*
  - Adicione todos os arquivos da pasta
- git add .

  - Arquivos e subpastas

- clear limpa o terminal

- "git rm --cached \<file>..." to unstage

  - unstage : retirar do estágio de controle
  - `-r` para remover _recursively_

- git commit -m"Comentário"

  - Confirmar/Submeter as alterações no computador local
  - O trabalho está pronto _localmente_

- git push
- git push origin main

  - Empurrados para o servidor, upload dos arquivos, subir pra nuvem, para GitHub

- Incremental

  - Toda vez que eu faço um add, o artefato é adicionado naquele ponto no tempo.

- Qual a única coisa que sobe para o servidor no comando git push?
  - as alterações de cada git commit

## Folha de dicas de Git

[Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

**© 2022 Zépa Software**
