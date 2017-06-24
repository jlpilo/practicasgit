**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

*git reset --hard HEAD~1:* con reset HEAD~1 retrocedo un commit pero dejando los cambios en el staying area. Para borrar cambios del working copy necesito el modificador --hard


**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

*git reflog*: para ver los commit por los que he ido pasado y localizo el commit en el que estaba antes de deshacer el commit del punto anterior.

*git reset --hard 7766259*: me muevo al commit que he localizado y con --hard modifico el contenido del workimg copy para que se vean los cambios en le archivo.


**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

*git merge master*: nos devuelve el mensaje *Already up-to-date* no se ha hecho el merge ya que la rama master es un aparte de la rama styled, por tanto no ha habido ningún conflicto.


**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

*git checkout styled* para cambiarme a la rama styled

*git merge htmlify" hay un conflicto en el contenido ya que el arhivo git-merge lo hemos modificado en las dos ramas y tiene distinto en cada una de ellas


**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

*git checkout master* para cambiarme a la rama master

*git merge styled* no provoca conflicto porque ambas ramas están el la misma linea


**- ¿Qué comando o comandos utilizaste en el paso 25?**

*git config alias.graph "log --graph --decorate --pretty=oneline"* para crear el alias graph

*git graph* para mostar el grafo


**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si prodria ser un fast forward ya que las dos ramas están en la misma linea


**- ¿Qué comando o comandos utilizaste en el paso 27?**

*git reset HEAD~1* deshago el merge pero los cammbio permanecen en el staying area sin pasar al working coy


**- ¿Qué comando o comandos utilizaste en el paso 28?**

*git checkout -- git-nuestro.md* se descartan los cambios del working copy


**- ¿Qué comando o comandos utilizaste en el paso 29?**

*git branch -D title**


**- ¿Qué comando o comandos utilizaste en el paso 30?**

*git reflog* para localizar el identificador del merge

*git checkout adead45* para rehacer el merge


**- ¿Qué comando o comandos usaste en el paso 32?**

*git checkout b4b1d4f*


**- ¿Qué comando o comandos usaste en el punto 33?**

*git checkout d45ffaf*

