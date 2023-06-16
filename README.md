# comandos-git

<img src="https://blog.geekhunter.com.br/wp-content/uploads/2020/08/comandos-git.png">

*Para criar pasta:*
<br>
``mkdir "[nome-da-pasta]"``

*Selecionar a pasta:*
<br>
``cd "[nome-da-pasta]"``

*Inicializar um repositório git:*
<br>
``git init``

Sair da pasta:
<br>
``cd ..``

*Criar um arquivo:*
<br>
``echo "# "[nome da pasta]"" >> "[arquivo.extensao]" ou touch "[arquivo.extensao]"``

*Listar o conteúdo do diretorio:*
<br>
``ls``

*Adicionar arquivos ou pastas:*
<br>
``git add "[arquivo/pasta]"``

*Adicionar todos os arquivos ou pastas:*
<br>
``git add .``

*Desfazer um add específico:*
<br>
``git reset "[nome-do-arquivo]"``

*Desfazer um add geral:*
<br>
``git reset``

*Desfazer o último commit, mantendo as alterações feitas no arquivo:*
<br>
``git reset --soft HEAD~1``

*Desfazer o último commit, removendo as alterações feitas no arquivo:*
<br>
``git reset --hard HEAD~1``

*Registrar um comentário (commit):*
<br>
``git commit -m ""[comentário]""``

*Verificar o status dos arquivos/diretórios e modificações realizadas:*
<br>
``git status``

