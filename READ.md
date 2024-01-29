# Lista de Comandos Git

- git init: cria um novo repositório local 

- git add: adiciona conteúdo à fila de commits (staged);

- git diff: compara os arquivos já commitados com os arquivos atuais

- git commit -m: commita arquivos

- git push: envia os commits locais ao repositório remoto;

- git pull: obtém os dados do repositório remoto (Fetch + merge)

- git status: indica a situação dos arquivos em relação ao estado atual da branch;

- git branch: lista as branches do repositório;

- git switch “branch alvo”: troca a branch para a branch alvo;

- git log: listagem dos commits feitos

- git checkout: navega entre branches e commits

- git clean: remove arquivos não rastreados

- git reset —hard: tira tudo do stage e dos commits, mantém tudo do modo inicial do commit

- git update-index —skip-worktree <nome do arquivo>: desconsidera o arquivo indicado
  
- git clone <nome do repositório> <nova pasta com o repositório>: clona um repositório em alguma pasta

- git remote: lida com o repositório remoto

- git merge <branch alvo>: traz as alterações presentes na branch alvo para a branch atual
 
- git tag <nome da tag>: cria uma tag no commit atual

- git stash: salva mudanças em uma área temporária

- git revert: descarta as mudanças de um commit

- git rebase <branch>: obtém commits anteriores de uma outra branch para que ambas tenham o mesmo ponto de partida

- git fetch: obtém dados so servidor remoto, sem realizar merge com os arquivos locais

- git cherry-pick <hash de commit>: obtém os dados de um único commit do repositório

- git bisect: utiliza busca binária para encontrar em qual commit alguma mudança apareceu pela primeira vez
