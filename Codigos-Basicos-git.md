### *Resumo das aulas do professor Otávio Reis*

##### Comandos básicos do Prompt para windows

- dir :arrow_forward: mostra os diretórios
- cd / :arrow_forward: acessar o C:
- cd + "nome da pasta" :arrow_forward: acessar a pasta "nome da pasta"
- cd .. :arrow_forward: retorna uma ação(retorna uma pasta)
- cls :arrow_forward: limpa tela do prompt de comando
- mkdir + "nome do diretório" :arrow_forward: cria um diretório
- echo "nome do diretório" > "nome do arquivo" :arrow_forward: cria um arquivo dentro do diretório
-  del + "nome do arquivo" :arrow_forward: deletar arquivo
- rmdir + "nome do diretório" /s /q :arrow_forward: deleta pasta



#### Git Here

##### sha1

Gera um Conjunto de 40 caracteres que determinam aquele arquivo ou programação.

- openssl sha1 "nome do arquivo".txt :arrow_forward: gera uma chave de 40 caracteres

#### Sistema de segurança do Git

- Commit :for tree, author, comitter
- tree: blob, blob...
- blob: contém meta dados, tamanho do arquivo, tipo de objeto

#### Comandos básicos Gitbash here:happy:

- ls :arrow_forward: listar
- ls -a :arrow_forward: mostras diretórios ocultos
- git config -global user.email "email"
- git config user.name "nome"
- echo > "nome do arquivo" :arrow_forward: criar arquivo
- git init :arrow_forward: criar pasta .git no diretório(pasta oculta)
- git add . :arrow_forward: adicionar mudanças que não estão no staged
- git commit -m "nome do commit" :arrow_forward: vai ser gerado números iniciais do sha1 que identifica o commit
- git reflog :arrow_forward: visualiza todas as versoes anteriores
- git branch :arrow_forward: visualiza as branchs
- git branch "nome da nova branch" :arrow_forward: criar uma nova branch
- git checkout "nome da branch" :arrow_forward: trocar de branch
- git pull "codigo do repositório" :arrow_forward: puxar do github para maquina
- git push origin "nome da branch" :arrow_forward: enviar para github
