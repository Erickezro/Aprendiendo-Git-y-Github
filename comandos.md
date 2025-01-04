**git config --global user.name "<USER_NAME>"**
Configura el nombre de usuario global para todos los repositorios.


**git config --global user.email "<USER_EMAIL>"**
Configura el correo electrónico global que se asociará con los commits.


**git config --list**
Muestra la configuración de Git para el repositorio actual.


**git config --global --list**
Muestra la configuración global de Git (aplicada a todos los repositorios).


**git config --global init.defaultBranch main**
Establece "main" como el nombre predeterminado para la rama principal al inicializar nuevos repositorios.


**git init**
Inicializa un nuevo repositorio Git en el directorio actual.


**git status**
Muestra el estado del repositorio (archivos modificados, en staging, etc.).


**git add mi-archivo.txt**
Agrega "mi-archivo.txt" al área de staging (preparado para commit).


**git rm --cached <file>**
Elimina un archivo del área de staging sin borrarlo del sistema de archivos.


**git commit -m "Agregar texto"**
Realiza un commit con el mensaje "Agregar texto".


**git log**
Muestra el historial de commits en el repositorio.


**git add .**
Agrega todos los archivos modificados al área de staging.


**git commit**
Abre el editor de texto para escribir el mensaje del commit.


**git config --global core.editor "code --wait"**
Asocia Visual Studio Code como el editor predeterminado para Git y espera a que se cierre para continuar, funcione el comando anterior


**git commit --amend**
Modifica el último commit (permite cambiar el mensaje o agregar más archivos).


**git reset --soft HEAD~1**
Deshace el último commit, manteniendo los cambios en staging.
