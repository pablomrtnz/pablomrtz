**Ordenes básicas de Git**

Iniciar repositorio:
~~~
git init
~~~

Comprobar:
~~~
git status
git log --graph --all
~~~

Comprueba el hash:
~~~
git log
~~~

Cambiar variables de configuración de nombre y correo:
~~~
git config --global user.email "<email>"
git config --global user.name "<nombre>"
~~~

Añadir ficheros al area de preparación:
~~~
git add <fichero>
~~~

Hacer commit:
~~~
git commit -m "<nombre commit>
~~~

Crear una etiqueta en un commit:
~~~
git tag <nombre_de_la_etiqueta> <hash_del_commit>
~~~

Fusionar ramas:
~~~
git merge <rama_a_fusionar>
~~~

Crear nueva rama:
~~~
git branch <nombre_rama>
~~~

Movernos a otra rama:
~~~
git checkout <nombre_rama>
~~~

Hacer commit:
~~~
git commit -m "<nombre commit>
~~~

Ver diferencias entre dos commits:
~~~
git diff <commit_1>..<commit_2>
~~~

Clonar repositorio:
~~~
git clone <URL_o_RUTA_repositorio>
~~~

Ver repositorios remotos:
~~~
git remote -v
~~~

Renombrar repositorio remoto:
~~~
git remote rename <nombre_actual> <nuevo_nombre>
~~~

Actualizar información de repositorio remoto (no incorpora los cambios):
~~~
git fetch
git fetch <nombre_remoto>
~~~

Enviar cambios locales al repositorio remoto:
~~~
git push
git push <nombre_remoto> <nombre_rama>
~~~

Equivalente a hacer un fetch y un merge a la vez:
~~~
git pull
git pull <nombre_rama> <nombre_remoto>
~~~
