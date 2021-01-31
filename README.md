# :man_technologist: Curso - Github
### Repositório feito apenas para meu aprendizado (testes) em git e github

## Comandos básicos

* **git version**
>Mostra a versão do git instalada

* **git init**
>Inicializa um repositório git vazio

* **git log**
>Exibe os registros log do commit

* **git log --oneline**
>Exibe os registros log do commit em uma linha cada

* **git status**
>Exibe a condição da árvore de trabalho

* **git add >arquivo<**
>Adiciona o conteúdo do arquivo ao índice

* **git add .**
>Adiciona o conteúdo de todos os arquivos ao índice

* **git commit -m 'comentario'**
>Grava as alterações feitas no repositório

* **git branch**
>Lista as branchs

* **git branch >nome<**
>Cria uma branch

* **git branch -d >nome<**
>Deleta a branch

* **git checkout >nome da branch<**
>Troca a branch

* **git checkout -b >nome da branch<**
>Cria uma branch e faz a troca para ela

* **git merge >nome da branch<**
>Une históricos de desenvolvimento

* **git rremote add origin >https://...<**
>Cria um repositório remoto

* **git push origin >branch<**
>Atualiza uma referência remota para uma origin a partir de uma referência local (empurra)

* **git pull origin >branch<**
>Atualiza uma referência local a partir de uma referência remota (puxa)

* **git reset --soft >commit<**
>Não toca no arquivo de índice ou na árvore de trabalho (mas redefine o cabeçalho para _commit_, assim como todos os modos fazem). Isso deixa todos os seus arquivos alterados como "Changes to be committe" (Alterações onde serão realizados os commits), como o git status colocaria.

* **git reset --mixed >commit< ou git reset >commit<**
>Redefine o índice, mas não a árvore de trabalho (ou seja, os arquivos alterados são preservados, mas não marcados para um commit) e relata o que não foi atualizado. Esta é a ação predefinida.

* **git reset --hard >commit<**
>Redefine o índice e a árvore de trabalho. Quaisquer alterações nos arquivos rastreados na árvore de trabalho desde _commit_ serão descartados.