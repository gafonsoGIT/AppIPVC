# AppIPVC

---------------------- Git ---------------------
olá
Nota:

- Versões são controladas no master branch(versões deployes)
- Ter em atenção, trabalhar sempre sobre a branch de developer e respectiva feature.
- Ter em atenção, não trabalhar sobre as branchs origin/

Comandos:

//criar nova branch
git checkout -b nomedaBranch

//criar nova branch sobre a branch developer
git checkout -b nomedafeature developer

//como dar merge da feature
git merge --no-ff

Passos:

1. git checkout -b nomedafeature developer

//para deixar o historica/ atenção estar dentro da branch developer para dar merge

2. git merge --no-ff nomedafeature

//ver se os files estão iguais aos da branch

3. Verificar se o merge ficou bem feito

4. git branch -d nomedafeature

---------------------------- Componentes -----------------------------

Routing - Guarda todos os componentes e respetiva lógica de routing da App.
