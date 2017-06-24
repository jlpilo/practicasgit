**- �Qu� comando utilizaste en el paso 11? �Por qu�?**

*git reset --hard HEAD~1:* con reset HEAD~1 retrocedo un commit pero dejando los cambios en el staying area. Para borrar cambios del working copy necesito el modificador --hard


**- �Qu� comando o comandos utilizaste en el paso 12? �Por qu�?**

*git reflog*: para ver los commit por los que he ido pasado y localizo el commit en el que estaba antes de deshacer el commit del punto anterior.

*git reset --hard 7766259*: me muevo al commit que he localizado y con --hard modifico el contenido del workimg copy para que se vean los cambios en le archivo.


**- El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?**

*git merge master*: nos devuelve el mensaje *Already up-to-date* no se ha hecho el merge ya que la rama master es un aparte de la rama styled, por tanto no ha habido ning�n conflicto.


**- El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?**

*git checkout styled* para cambiarme a la rama styled

*git merge htmlify" hay un conflicto en el contenido ya que el arhivo git-merge lo hemos modificado en las dos ramas y tiene distinto en cada una de ellas


**- El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?**

*git checkout master* para cambiarme a la rama master

*git merge styled* no provoca conflicto porque ambas ramas est�n el la misma linea


**- �Qu� comando o comandos utilizaste en el paso 25?**

*git config alias.graph "log --graph --decorate --pretty=oneline"* para crear el alias graph

*git graph* para mostar el grafo


**- El merge del paso 26, �Podr�a ser fast forward? �Por qu�?**

Si prodria ser un fast forward ya que las dos ramas est�n en la misma linea


**- �Qu� comando o comandos utilizaste en el paso 27?**

*git reset HEAD~1* deshago el merge pero los cammbio permanecen en el staying area sin pasar al working coy


**- �Qu� comando o comandos utilizaste en el paso 28?**

*git checkout -- git-nuestro.md* se descartan los cambios del working copy


**- �Qu� comando o comandos utilizaste en el paso 29?**

*git branch -D title**


**- �Qu� comando o comandos utilizaste en el paso 30?**

*git reflog* para localizar el identificador del merge

*git checkout adead45* para rehacer el merge


**- �Qu� comando o comandos usaste en el paso 32?**

*git checkout b4b1d4f*


**- �Qu� comando o comandos usaste en el punto 33?**

*git checkout d45ffaf*

