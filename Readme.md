Olá, esse projeto é para prática e estudo sobre GIT;


-Formas de utilizar o GIT:
    -Pelo terminal do VScode
    -Pelo GIT Bash

-Comandos:

    -git init (inicializa o GIT, nem sempre master será a linha principal, GIT está mudando a nomenclatura para "main")

    -git add Readme.md(ou o nome do arquivo/ serve para adicionar o arquivo) 
                ou 
    -git add . (ao contrário de adicionar só um arquivo para alterações e mandar para o stage, ele adiciona *TODOS* arquivos que está disponivel)
     -Se usar o Git status para averiguar isso:
        $ git status
        On branch main
        Your branch is up to date with 'origin/main'.

        Changes to be committed:
        (use "git restore --staged <file>..." to unstage)
        new file:   ProjetoDeFato.md (mostra que foi adicionado outro arquivo)
        modified:   Readme.md


    -git status (mostra o status, qual arquivo foi adicionado na área de stage)

    -git commit -m "primeiro commit" (adicionando alterações, ou salvando modificações no projeto)

    -git branch -M "main"  (mudando a branch que está, no caso mudando de master para "main", racicionio de mudar de linha cronológica)

    -git remote add origin link.git (adiciona e cria a conexão entre o repositório local com o do Github/ o "origin" é só o nome padrão do rep do Github, é alteravel)
        -Só precisa usar o comando 1 vez para criar a conexão

    -git push -u origin main (por último, manda tudo para o Github, "empurra")
    
    -git checkout "main" (volta para a branch desejada)

    -git checkout -b "novo-botao" (criando uma nova Branch,e com o checkout, saindo da branch que eu estava(main) e indo para a branch "novo botao")
    
    -git merge nome-da-branch (juntar branch com a principal)

    -git clone <link> (ele cópia um repositório existente.)

    -git pull ( Pega a atualização do git clone. (Antes entrar com cd).)

    -pull request (sugestão de alteração para outra pessoa)
