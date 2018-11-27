Git guía básica
===============
en Mac para trabajar con un usuario diferente al que está por default, se utiliza el comando: 
```bash
	git config credential.username vcobop
```

Para crear un repositorio nuevo
##

se crea en el pc un directorio

```bash
	mkdir <dirname>
	cd <dirname>
```

Para crear el repositorio

```bash
	git init
```

Para configurarlo

```bash
	git config —global user.name <name>
	git config —global user.email <email>
```
Para hacer el enlace primero se debe crear desde la página web del usuario un repositorio nuevo, quitando la opción de creación de README.md automático.

Para configurar la dirección del acceso remoto y enlazarlo:

```bash
	git remote add origin <linkrepo>
```

El link se encuentra en la página web del repositorio.
 
Para agregar un archivo
##

Se crea el archivo.

Para agregarlo al repositorio:
```bash
	git add <filename>
```
Para subirlo al repositorio remoto (online) o actualizarlo:
```bash
	git commit -m “comentario”
```

Para actualización de algún elemento del repositorio, primero se debe actualizar los elementos de la carpeta, se hace así:

```bash
	git pull
```

cuando ya se han actualizado, se puede empezar a editar.

Para subirlo nuevamente se hacen los pasos anteriores con git add y git commit -m

Por ultimo de debe actualizar nuevamente en el repositorio web los documentos, de esta manera:

```bash
	git push -u origin master
```

Por ultimo si se quiere revisar el estado del repositorio:
```bash
	git status
```

Para arrastrar un repositorio 
```bash
	git clone <link>
```

Cosas para hacer
================
- [x] crear el repositorio con el respectivo README.

- [x] Subir el contenido de la clase 1

- [ ] Subir el contenido de la clase 2

Este es el [enlace](https://github.com/JoseMontanaC/Curso-Konrad-Lorentz) del repositorio del paco.


