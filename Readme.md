# GIT +GITHUB

#### Comandos para inicializar sesión en GIT
```js
'git config --global user.name "userName"' --Se usa para establecer usuario
'git config --global user.email "test@test.com"' --Se usa para establecer el correo electronico
"git config --global -e" -Se usa para ver el usuario y email configurado y poder cambiarlo si se requiere
```
#### Comandos para manejar GIT

Comandos mas importantes 
```JS
"git fetch" -- Se usa para traer los cambios del repositirio incluyendo ramas
"git pull" -- Se usa para bajar los cambios de una rama especifica y hacerles automerge
"git checkout <branchName>" -Sirve para cambiar a una rama especifica
"git merge <branchName>" --Sirve para integrar los ultimos cambios de una rama especifica dentro de la rama que en la que estas ubicado
"git add" -- Se usa para agregar en el stage los cambios reliazados manualmente
'git commit -m "mensajeString"' --Se usa para colocar un mensaje al commit
"git push" --Se usa para mandar tus cambios de tu repo local al remoto
```

Comandos generales 
```JS
"git init" -Crea el repositorio local para poder comenzar a trabajar
"git help" -- Se usa para visualizar todos los comandos que se pueden usar en git
"git status" --Sirve para ver que archivos estan en el state y cuales no se han añadido
"git status --short" --Sirve para ver de una manera mas comprimida la informacion de
"git log" --Muestra el historial de commits que se han realizado en el repositorio
"git log --oneline" --Muestra los comits de una manera mas comprimida mostrando unicamente el hash y el comit
```

Manejo de archivos y state
```JS
"git add" -- Se usa para agregar en el stage los cambios reliazados localmente
 "git add <docName>" --Sirve para subir un unico arvhivo al state
 "git add ." -Se usa para subir todos los arvhivos al state pero solo de la ruta especifica en la que se esta trabajando. (util si trabajas con repositorios que tienen backend y frontend juntos y solo trabajas en alguno de ellos)
 "git add --all" -Se usa para subir todos los archivos al state del repositirioo local incluyendo subcarpetas etc.(util cuando tu repositirio contiene solo tus cambios, osea solo es de frontend).
 "git add *.<extension>" --Se usa para subir al state todos los archivos que compartan una extencion ejemplo ('git add *.js')
"git reset <archivoName>" -Saca el archivo del state en caso de que no se quiera
"git status" --Sirve para ver que archivos estan en el state y cuales no se han añadido
"git checkout -- ." --Sirve para reconstruir el archivo a como estaba antes del ultimo comit
```

Manejo de commits
```JS
'git commit -m "mensajeString"' --Se usa para colocar un mensaje al commit
'git commit -amend -m "mensajeString modificado"' --Se usa para cambiar el mensaje de un commit
```


Manejo de repositorio local y remoto
```JS
"git init" -Crea el repositorio local para poder comenzar a trabajar
"git fetch" -- Se usa para traer los cambios del repositirio incluyendo ramas
"git pull" -- Se usa para bajar los cambios de una rama especifica y hacerles automerge
"git push" --Se usa para mandar tus cambios de tu repo local al remoto
```

Manejo de ramas del repositorio e integración entre ellas
```JS
"git branch" --Sirve para ver las ramas que tiene el repositorio, locales y remotas y ver en cual se esta trabajando.
"git checkout <branchName>" --Sirve para cambiar a una rama especifica
"git merge <branchName>" --Sirve para integrar los ultimos cambios de una rama especifica dentro de la rama que en la que estas ubicado
"git branch -m <nombreBranch> <nombreNuevo>" --Sirve para cambiar el nombre de una rama especifica
```