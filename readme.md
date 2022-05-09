# GIT Basico

## instalacion 

instalacion desde el asistente de git

## comandos para credendiales en nuestro equipo

```

git config --global user.name "nombredeusuario"
git config --global user.mail "correo"
```

## crear un repositorio git
```
git init
```
Ver la situacion en la que estan los cambios desde el ultimo comit
```
git status
```
## añadir archivos al staging area

añade todos los cambios pendientes

```
git add -A
```

## crear un commit

Para guardar un conjunto de cambios y crear un punto de control usamos los comit 

```
git comit -m "mensajes del comit"
```

## deshacer cambios a partir de los comit

2 opciones

```  
git soft "codigo-comit"

con --soft podemos volver a un comit anterior sin deshacer cambios