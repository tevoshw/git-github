git branch <nome-da-branch>: cria uma branch
git branch: visualiza todas as branchs do local
git branch -r: vizualiza todas as branchs que tem no remoto
git checkout: troca de uma branch para outra
git fetch: sincroniza as alterações do repositório remoto com o repositório local
git merge: junta duas branchs
git pull: fetch + merge
git status: verifica o status das alterações atuais
git log: histórico dos commits ja feitos
git diff: visualiza as diferenças do arquivo atual para o último commit realizado
git push -u origin <nome-da-branch>: envia uma branch do local para o remoto (só é necessário uma vez)
git restore: descarta as alterações feitas no arquivo atual e restaura tudo para o último commit feito
git branch -d <nome-da-branch>: deleta uma branch opcionalmente (local)
git branch -D <nome-da-branch>: deleta uma branch obrigatoriamente (local)
git push origin --delete <name>: deleta uma branch (remoto)