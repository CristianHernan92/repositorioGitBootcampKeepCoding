
-	¿Qué comando utilizaste en el paso 11? ¿Por qué?

-utilicé el comando “git reset —hard HEAD~1”, porque con este comando estamos regresando al commit anterior en el cual estaba  antes de haber creado el commit que queremos deshacer  y con  “—hard” le estamos diciendo que no cambie el working copy

-	¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

-“git reflog” para saber el id del commit que se había deshecho luego  “git reset —hard [id del commit]”

-	El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

-no, porque styled ya contiene a la rama main, es decir, ya contiene al  commit de la rama main (fast foward)

-	El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

-sí, causó conflicto, porque se tuvo que generar un nuevo commit para unir ambas ramas (no fast forward) para no perder el commit que estába apuntando styled y se encontraron conflictos entre ambos commits (el commit de la rama head con el commit de la rama htmlify)

-	El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

-no causó ningún conflicto, porque se produjo el merge mediante el modo “fast forward” ya que no se pierde el commit de la rama main al irse a la rama styled

-	¿Qué comando o comandos utilizaste en el paso 25?

-“git log —graph —online”

-	El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

-sí, podría ser fast forward porque la rama title contenía al commit de la rama main, es decir existe la  linea por así decirlo

-	¿Qué comando o comandos utilizaste en el paso 27?

-“git reset HEAD~1”

-	¿Qué comando o comandos utilizaste en el paso 28?

-“git restore git-nuestro.md”

-	¿Qué comando o comandos utilizaste en el paso 29?

-“git branch -D title”

-	¿Qué comando o comandos utilizaste en el paso 30?

-“git reflog” y luego “git reset —hard [id del commit]”

-	¿Qué comando o comandos usaste en el paso 32?

-“git reflog” y luego “git reset —hard [id del commit]”

-	¿Qué comando o comandos usaste en el punto 33?

-“git reflog” y luego “git reset —hard [id del commit]”
