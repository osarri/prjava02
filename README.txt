1)
  git checkout -b branca00
  git status
  
5)
  git checkout master
  git status
  git log master

10)
  git checkout master
  git merge branca00

14)
  git push -u origin branca01

Preg 6)
  Veremos que no está la última línea debido a que ahora estamos trabajando sobre el archivo prjava02.java 
  de la rama master, no de la branca00, por lo cual no podremos ver la informacion almacenada en esa branca.

Preg 7)
  Veremos que  está la última línea debido a que ahora estamos trabajando sobre el archivo prjava02.java de la rama branca00, 
  no la master, por lo cual  podremos ver la informacion almacenada en esa branca00.

Preg 12)
  Se ha actualizado cuando hemos actualizado la branca master,ya que en un apartado anterior hemos fusionado la branca00
  con la branca master,lo que quiere decir que al actualizar una la otra se actualiza tambien.
  Por lo tanto la unica branca que ha cambiando es la branca master.
