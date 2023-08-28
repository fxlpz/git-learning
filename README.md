# git-learning

git init 
- iniciar novo projeto com git;

git add <nome do arquivo> / .
- add os arquivos que estão prontos para serem commitados;

git commit -m "mensagem-de-commit"
- commita os arquivos no histórico;

git log
- mostra os ultimos commits, log de alterações;

git status
- mostra como esta o estado da nossa ramificação;

git diff
- mostra o que foi alterado;
- o que tem de alteração na ramificação; 

git merge
- faz o merge de ramificações, mescla ramificações;

git branch
- mostra a branch atual;

git branch -b <nome-da-branch>
- cria uma nova branch a partir do historico atual da branch que estamos;

git checkout <nome-branch>
- muda pra essa branch;

git checkout -b <nome-nova-branch>
- cria uma nova branch a partir da branch atual que estamos;

git remote add <nome-remoto> <url>
- add um novo repositorio remoto;

git push <nome-remoto> <nome-da-branch>
- manda nossas alteraçoes locais para o repositorio remoto, para cada branch;

git pull <nome-remoto> <nome-da-branch>
- pega as alterações do repositorio remoto e joga para nossa máquina; 

git fetch
- atualiza nosso historico local de acordo com o historico salvo no repositorio remoto (baixa as alterações feitas no remoto para nossa maquina);
- sync do local com o remoto


