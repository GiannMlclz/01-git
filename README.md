# Clase 05 - git

## Para crear un repositorio de GIT

```sh
git init
```

## ver en que estado estan los archivos y en que area

```sh
git status
```

## areas del repositorio de GIT

3 Áreas

* Working directory (WD): Dierectoro de trabajo se va agregando o quitando los archivos durante el desarrollo
* Starting Area (SA): (Área de control de cambios. Area temporal/Intermedia) <!-- Area de confirmacion -->
* Local repo (RP): (Una caja donde voy a ir teniendo todas las fotos que vaya sacando)

## Estados de los archivps

* Untracked: (Archivos archivos que están en el WD pero GIT no le esta dando seguimiento)
* Unmodified: (Archivos que GIT ya estas siguiendo y con respecto al WD, no fueron modificados)
*Modiefied: Archivos que se encuentran en el repositorio (Estan siendo seguidos por GIT) pero difieren con lo que se encuentra actualmente en el WD
* Staged: Archivos que estam en el area temporal/Intermedia

# Agrego al area de confirmacion el archivo/archivos

```sh
git add <nombre-archivo>
git add <nombre-archivo> <nombre-archivo> <nombre archivo>
git add. # agrega todos los archivos.