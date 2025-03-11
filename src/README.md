Hola primer commit

Hola segundo commit

<<<<<<< HEAD
# commits de lider
git checkout -b "nombre de la rama"

git commit -a -m "nombre del commit"
Estos son commits en la rama lider

git commit -a -m "nombre del commit"
Mas commits rama lider 2

git commit -a -m "nombre del commit"
Muchos mas commits lider 3

=======
>>>>>>> master
## Comandos colaborador 
```bash
# Crea la rama de colaborador
git checkout -b colaborador
# commit a 
git commit -a -m "A"
# commit B
git commit -a -m "B"
# commit C
git commit -a -m "C"
```

# Unir las ramas con merge
```bash
# Hacer checkout a la rama master
git checkout master

# Merge con la rama colaborador
git merge colaborador

# Hacer el commit del merge
git commit -a -m "merge con colaborador"
```