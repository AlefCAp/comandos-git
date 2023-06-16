# comandos-git

- Para criar pasta:
mkdir "[nome-da-pasta]"
- Selecionar a pasta:
cd "[nome-da-pasta]"
- Inicializar um repositório git:
git init
- Sair da pasta:
cd ..
- Criar um arquivo:
echo "# "[nome da pasta]"" >> "[arquivo.extensao]" ou touch "[arquivo.extensao]"
- Listar o conteúdo do diretorio:
ls
- Adicionar arquivos ou pastas:
git add "[arquivo/pasta]"
- Adicionar todos os arquivos ou pastas:
git add .
- Desfazer um add específico:
git reset "[nome-do-arquivo]"
- Desfazer um add geral:
git reset
- Desfazer o último commit, mantendo as alterações feitas no arquivo:
git reset --soft HEAD~1
- Desfazer o último commit, removendo as alterações feitas no arquivo:
git reset --hard HEAD~1
- Registrar um comentário (commit):
git commit -m ""[comentário]""
- Verificar o status dos arquivos/diretórios e modificações realizadas:
git status

