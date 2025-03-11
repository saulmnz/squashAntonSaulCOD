Hola primer commit

Hola segundo commit

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