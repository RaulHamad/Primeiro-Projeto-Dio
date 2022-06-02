### *Resumo das aulas da professora Otávio Reis*

##### Comandos básicos do Prompt para windows

- dir - mostra os diretórios
- cd / - acessar o C:
- cd + "nome da pasta" - acessar a pasta "nome da pasta"
- cd .. - retorna uma ação(retorna uma pasta)
- cls - limpa tela do prompt de comando
- mkdir + "nome do diretório" - cria um diretório
- echo "nome do diretório" > "nome do arquivo" - cria um arquivo dentro do diretório
-  del + "nome do arquivo" - deletar arquivo
- rmdir + "nome do diretório" /s /q - deleta pasta



#### Git Here

##### sha1

Gera um Conjunto de 40 caracteres que determinam aquele arquivo ou programação.

- openssl sha1 "nome do arquivo".txt - gera uma chave de 40 caracteres

#### Sistema de segurança do Git

- Commit - tree, author, comitter
- tree - blob, blob...
- blob - contém meta dados, tamanho do arquivo, tipo de objeto

#### Comandos básicos Gitbash here:happy:

- ls - listar
- ls -a - mostras diretórios ocultos
- git config -global user.email "email"
- git config user.name "nome"
- echo > "nome do arquivo" - criar arquivo
- git init - criar pasta .git no diretório(pasta oculta)
- git add . - adicionar mudanças que não estão no staged
- git commit -m "nome do commit" - vai ser gerado números iniciais do sha1 que identifica o commit
- git reflog - visualiza todas as versoes anteriores
- git branch - visualiza as branchs
- git branch "nome da nova branch" - criar uma nova branch
- git checkout "nome da branch" - trocar de branch
- git pull "codigo do repositório" - puxar do github para maquina
- git push origin "nome da branch" - enviar para github
