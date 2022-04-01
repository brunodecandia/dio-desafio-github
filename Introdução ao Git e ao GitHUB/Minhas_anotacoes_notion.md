# Introdução ao Git e ao GitHub

- **Chave ssh e Token**
  
  
    06:25 criacao do ssh
    
    ssh-keygen -t ed25519 -c brunodecandia@gmail.com
    
    cd → change directory
    
    cat 
    
    pwd → mostra o caminho q estou no terminal
    
    11:20 proximo comando
    
    17:10 comeca o tutorial para linux 20:35
    
    22:22 token de acesso pessoal
    
- **iniciando o git e criando commit**
  
    ```bash
    git init # inicial um repositorio na pasta atual
    git add <nome_do_arquivo> # adiciona o arquivo para ser commitado
    git add * # adiciona todos os arquivos para serem comitados
    git commit -m "commit inicial" # comita os arquivos com a mensagem "commit inicial"
    
    mkdir <nome_da_pasta> # cria uma pasta
    
    ctrl+L # limpa terminal
    ls -a # mostra os arquivos ocultos do sitema
    
    git config --global user.email "brunodecandia@gmail.com"
    git config --global user.name "Bruno"
    
    git config --list
    
    git status
    
    mv <strogonoff.md>  ./<receitas/> # move arquivo "strogonoff.md" para o repositorio "receitas"
    
    git rm <file> #pesquisar, parece ser o oposto ao git git add
    
    echo > README.md # cria um readme em markdown
    
    git remote add origin <https://github.com/brunodecandia/livro-receitas.git> # seta repositorio remoto no github
    git remote -v # exibe os repositoris remotos cadastrados
    
    git push origin master # empura arquivos para a origin vindos da master
    
    git push <origin> <master>
    
    git pull origin master #puxa conteudo da origin pra master (do github para o repositorio local)
    
    git clone <endereço_do_repositorio>
    ```
    
    
    
  [Git - Configuração Inicial do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git)

```bash
cd (c)hange (d)irectory
mkdir (m)a(k)e (dir)ectory
rm (r)e(m)ove
chown (ch)ange (own)er
pwd (p)rint (w)orking (d)irectory
cd $HOME #vai para home a partir de qlqr diretorio
cd ~ # mesma coisa q cd $HOME
cd ~/Documentos
cd / # vai para raizcd
```