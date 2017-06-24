1.  #### ¿Que comando utilizaste en el paso 11? ¿Porque?
	- git reset --hard HEAD~1
	- Porque deshace el ultimo **commit** y lo que esta en el *working copy*, el *staging area* queda vacio.

2. #### ¿Que comando o comandos utilizaste en el paso 12? ¿Por qué?
	- git reflog
	- git reset 1683f8
	- Con la opción **reflog** nos permite observar los *hash* de cada **commit**, y  con la opción **reset** hacemos el salto al **commit**

3. #### El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
	- git merge master 
	- No.

4. #### El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
	- git checkout styled 
	- git merge htmlify
	- No.
	   
5. #### El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
	- git checkout master
	- git merge styled
	- No.

6. #### ¿Qué comando o comandos utilizaste en el paso 25?
	- git log --graph

7. #### El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
	- git checkout master
	- git merge --no-ff title
	- Si, por que solo mueve el puntero a la rama absorvida *(title)*, incluyendo todo el trabajo de la rama absorvida *(title)*.

8. #### ¿Qué comando o comandos utilizaste en el paso 27?
	- git reset HEAD~1

9. #### ¿Qué comando o comandos utilizaste en el paso 28? 
  	- git merge --abort

10. #### ¿Qué comando o comandos utilizaste en el paso 29? 
	- git branch -D title

11. #### ¿Qué comando o comandos utilizaste en el paso 30? 
	- git reflog
	-  git reset eb37449

12. #### ¿Qué comando o comandos usaste en el paso 32?
	- git add .
	- git reset 25c25e

13. #### ¿Qué comando o comandos usaste en el punto 33?
	- git reset 9c4126a