# GIT Básico

## Instalación

Instalación desde el asistente de GIT

## Comandos para credenciales en nuestro equipo

```
git config --global user.name "nombre usuario"
git config --global user.email "correousuario"
```

## Crear un repositorio GIT

```
git init
```

## Comprobar el estado de GIT

Ver la situación en la que están los cambios desde el último commit

```
git status
```

## Añadir archivos al staging area

Añade todos los cambios pendientes

```
git add -A
```

## Crear un commit 

Para guardar un conjunto de cambios y crear un punto de control usamos los commit

```
git commit -m "mensajes del commit"
```

## Deshacer cambios a partir de los commit

Tenemos 2 opciones:

```
git reset --soft código-commit
```

Con --soft podemos volver a un commit anterior sin deshacer cambios

```
git reset --hard código-commit
```

Con --hard vuelve al commit anterior borrando el seleccionado y los siguientes