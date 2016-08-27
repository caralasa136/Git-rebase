# Git rebase

Existen dos formas en git de unir ramas, `git merge` y `git rebase`, la más común o más utilizada es `merge`.

Git rebase básicamente lo que hace es recopilar uno a uno los cambios confirmados en una rama, y reaplicarlos sobre otra. Utilizar rebase nos puede ayudar a evitar conflictos siempre que se aplique sobre commits que están en local. Si no tienen cuidado con ésto puede haber conflictos de commits.
Utilizando `git rebase` obtenemos un log de commits mucho mas sencillo. Nos permite tener mayor control de versión en pull requests. En vez de tener bifurcaciones como un `merge` queda de la siguiente manera una vez que hacemos `rebase`:

![Git rebase](http://www.solucionex.com/sites/default/files/blog_old/git_rebase.jpg)
