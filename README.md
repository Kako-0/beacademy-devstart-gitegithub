
# Git e GitHub

Repositório para compartilhar conhecimento sobre comandos gerais do Git e GitHub

## Comandos


#### &ensp; Cria um versionamento(.git) em uma pasta local. É o primeiro comando para se criar um repositório.
```bash
  $ git init
```
***

#### &ensp; Fornece informações sobre a branch atual e sua atual situação (untracked, modified...)
```bash
  $ git status
```

***

#### &ensp; Inclue a criação ou alterações de um arquivo para o próximo commit.
```bash
  $ git add
```
| Parâmetro      | Descrição                                   |
| :--------------| :------------------------------------------ |
| `. ou --all`| Adiciona todos os arquivos |
|`<nome-do-arquivo.extensão>`| Adiciona o arquivo citado|

***

#### &ensp; Permite que se crie um commit, ou seja, o git guarda o estado atual do seu repositório
```bash
  $ git commit
```
| Parâmetro      | Descrição                                   |
| :--------------| :------------------------------------------ |
| `-m <messagem>`| **Obrigatório**. A messagem sobre o que foi commitado |

***
#### &ensp; Permite apagar um arquivo no repositório Git que ainda não foi commitado
```bash
  $ git rm <nome-do-arquivo>
```
***
#### &ensp; Lista, em ordem cronológica inversa, os commits já feitos no repositório. Ou seja, os commits mais antigos são mostrados no final da lista.
```bash
  $ git log
```

***
#### &ensp; Usa-se este comando para criar, listar e excluir branches(ramificações).
```bash
  $ git branch
```
| Parâmetro      | Descrição                                   |
| :--------------| :------------------------------------------ |
| `<nome-da-branch>`| **Obrigatório.** Cria-se uma nova branch |
| `--list` ou apenas o comando| Lista todas as branches criadas|
| `-d <nome-da-branch>`| Deleta a branch citada|

***

#### &ensp; Usada para mudar de uma branch para outra
```bash
  $ git checkout
```
| Parâmetro      | Descrição                                   |
| :--------------| :------------------------------------------ |
| `-b <nome-da-branch>`| Cria-se uma nova branch e vai para esta.|

***

#### &ensp; Mescla a branch citada com a branch principal
```bash
  $ git merge <nome-da-branch> 
```
***

#### &ensp; Copia um repositório remoto para um repositório local linkando-o ao original
```bash
  $ git clone
```

***
#### &ensp; Esse comando envia para seu repositório remoto(GitHub) os commits feitos no repositório local.
```bash
  $ git push
```

***
#### &ensp; Atualiza o repositório local de acordo com a última versão do seu respectivo repositório remoto.
```bash
    $ git pull
```

***

#### &ensp; Salva as alterações sem commit para uso posterior
```bash
  $ git stash
```
| Parâmetro      | Descrição                                   |
| :--------------| :------------------------------------------ |
| `-u ou --include-untracked`| Salva arquivos também não rastreados.|
| `-a ou --all`| Engloba também arquivos ignorados|
|`list` | Lista todos os stashes criados|
| `pop`| Reaplica o stash criado mais recentemente|
|`pop stash@{1}`| Reaplica um stash específico, stash 1 neste caso|

***
