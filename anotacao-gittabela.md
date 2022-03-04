

# Tabelas de git #
Coluna de comandos git |  Coluna de git 
:------- | ------:
` identidade no git` | basta escrever  **git config --globar user.name "seu nome"** e **git config --global usar.email "seu email"** para dar finalidade a commit inicial.
`git init` | Vai dar iniciação a um repositório local de sua maquina. 
`git config --list`| Serve para analisar suas configurações no git.
`git pull` | Puxa repositório de origin e sincroniza com HEAD.
`git switch <branch>` | Muda para **branch**.
`git add* ` | vai iniciar a transferencia</br> do arquivo escolhido
`git add README.md` | *opcional* adicione o arquivo **README.md** para iniciar a transferencia.
`git commit -... "first commit(nome do arquivo na maquina)` | Realiza commit com arquivos colocados em cena </br> `-a` : adiciona todos arquivos em cena automaticamente (Que já estejam sendo rastreados). </br> `-m <mensagem>` : define nome da commit.
`git remote add origin URL\\https:github....`| Vai dar localidade ao seu repositorio (arquivo README.md) e exportar o arquivo/repositovio no seu github
`git push <origin main> <branch>` | Sobe repositório para o GitHib. </br> `-u` : define local remoto do repositorio. </br> `-f` : modo forçado.
  `git remote -v` | Vai verigicar seu URL de repositorios no GitHub que estão em ligação com a maquina de forma remota
  ` git rm ` | Remove arquivos **--cached** remove apenas do repositório local e mantém o arquivo no local de trabalho.* 
  ` git branch` | Mostra lista de branches do projeto`-d:` deleta branch.`-D :` deleta branch em modo forçado, mesmo que não tenha sido fundida.
`git remote` | Mostra repositórios remotos existentes. </br> `add <nome/origin>` : adiciona novo repositório remoto. </br> `rename <velho> <novo>` : renomeia repositório remoto. </br> `remove` : remove repositório remoto. </br> `set-head <nome>` : define como HEAD. </br> `-v` : modo verboso.
 
### Observação ###

>algumas alterações seram feitas eventualmente </br> estou apenas aplicando o básico de Git e GitHub aqui </br>Espero que sirva de aprendizado inicial desta ferramenta.

