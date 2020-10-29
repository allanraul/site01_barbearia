- [COMANDOS GIT](#comandos-git)
  - [INICIANDO UM REPOSITÓRIO](#iniciando-um-repositório)
  - [SINCRONIZANDO OS DADOS](#sincronizando-os-dados)
    - [Enviando informações para o github.com](#enviando-informações-para-o-githubcom)
    - [Recebendo informações para o github.com](#recebendo-informações-para-o-githubcom)
# COMANDOS GIT
## INICIANDO UM REPOSITÓRIO
1. Para iniciar um repositório, usar o `git init` dentro da pasta que você deseja monitorar as alterações nos arquivos/pastas;
2. Criar o arquivo `README.MD`; 
3. Usar o comando `git add` e em seguida, o nome do arquivo que eu desejo "comittar";
4. Usar o comando `git commit -m"Comentário da mudança do arquivo"`, utilizado para gravar as mudanças no arquivo.
5. Criar repositório no github.com;
6. Utilizar o comando `git remote add origin master` + URL do repositório criado no item 5.

## SINCRONIZANDO OS DADOS
### Enviando informações para o github.com
1. Utilizar o comando `git push origin master` 

### Recebendo informações para o github.com
1. Utilizar o comando `git pull origin master`