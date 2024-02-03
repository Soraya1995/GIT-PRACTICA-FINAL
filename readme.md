● ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  Utilice git reset hard HEAD~1 , porque queriamos perder staging area y tambien los cambios 
  realizado en working copy y dejar como al principio.
● ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
   utilice reflog para buscar el Id del commit y despues utilice el git
   checkout para retoceder y que volviera el commit 

  
● El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
  No me causo nigun conflicto. Porque me moví primero a la rama styled y luego
  ya realice el merge.

● El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
  No me surgio nigun problema, porque primero fui a al rama styled y hice
 el merge de ahí.

● El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
  No, porque primero pase a la rama main y relice el merge a styled.
● ¿Qué comando o comandos utilizaste en el paso 25?
   Utilice Git log -- graph
● El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
  Si , porque creo que es otra forma de unir las ramas diferente , pero que 
  se puede realizar también.
● ¿Qué comando o comandos utilizaste en el paso 27?
  git merge -- no -ff 
● ¿Qué comando o comandos utilizaste en el paso 28?
  git reset--hard HEAD~1
● ¿Qué comando o comandos utilizaste en el paso 29?
   git branch -D 
● ¿Qué comando o comandos utilizaste en el paso 30?
   utilice git reflog para buscar el Id del paso realizado
  y despues git reset para retroceder lo hecho.
● ¿Qué comando o comandos usaste en el paso 32?
  git reflot y git reset
● ¿Qué comando o comandos usaste en el punto 33?
   git reflog para buscar el id del commit y después git checkaout para ir.
