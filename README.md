# git_kc_14

# git_kc_14
- 11) ¿Qué comando utilizaste en el paso 11? ¿Por qué?
        git reset --hard HEAD~1
	Este comando vuelve el commit anterior sin traer los cambios del working copy.

- 12) ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué? 
	nano git-nuestro-md
Añadimos los cambios del punto 9.
	git add git-nuestro.md
	git commit -m “Fix commit”	
Sería volver a crear  un commit normal. Modificaciones con nano en el fichero    git-nuestro.md, con git add <file> añadimos los cambios y con git commit <file> realizamos los cambios.

13) El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
git merge main 
No, debido a no tener cambios en la rama main.

19)  El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
git checkout styled
git merge htmlify
Si tenemos un conflicto nos quedamos con los cambios de styled

 - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
git checkout main
git merge styled
No tenemos conflictos porque solo añade las modificaciones.

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
git merge title
Solo añade  una línea de código, porque git lo toma como fast-fordward.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

 - ¿Qué comando o comandos utilizaste en el paso 28? 
git restore git-nuestro.md
Con esto descartamos los cambios.

- ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title
- ¿Qué comando o comandos utilizaste en el paso 30? 
git reset --hard HEAD~1
git merge 87fd0fd
- ¿Qué comando o comandos usaste en el paso 32? 
git branch -D title htmlify styled
git reset --hard  HEAD~11
- ¿Qué comando o comandos usaste en el punto 33? 
git reflog 
git merge 87fd0fd
