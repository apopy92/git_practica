- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1, porque se ha hecho un commit antes y para dejar sin efecto ese commit y dejar mi working copy como estaba antes del commit

 - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
git reflog
git reset --hard 8f500a4
para deshacer el reset – hard anterior y dejando mi worhing copy como estaba antes
 - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
git merge master
no causo ningún conflicto porque el archivo git-nuestro.md modificado con el commit del paso 10 tiene tiene elos mismos LF que antes del commit
 - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si causo conflicto porque git-nuestro.md se modifico en la rama htmlify y no coincidia con el archivo git-nuestro.md de la rama styled
 - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No causo ningún conflicto porque el archivo git-nuestro.md tenia el mismo texto que el archivo git-nuestro,md de la rama styled
 - ¿Qué comando o comandos utilizaste en el paso 25?
Git log --graph
 - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Git merge –no-ff title estando situado en la rama master
- ¿Qué comando o comandos utilizaste en el paso 27?
git reset 7cf307c

 - ¿Qué comando o comandos utilizaste en el paso 28?
git restore git-nuestro.md

 - ¿Qué comando o comandos utilizaste en el paso 29? 
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog
git reset --hard c82f0ee
 - ¿Qué comando o comandos usaste en el paso 32?
git reflog
git reset 8fa1528

 - ¿Qué comando o comandos usaste en el punto 33?
git reflog
git reset e14b4d6
