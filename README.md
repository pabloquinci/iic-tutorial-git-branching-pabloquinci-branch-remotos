# Ejercicios
- Hay un archivo en la raíz del proyecto llamado .gitignore. ¿Qué utilidad tiene?
< br / > Es un archivo que nos permite ignorar ciertos archvios/directorios que le indiquemos para ser consierados como parte de la subida al repositorio

- ¿Qué tipo de archivos pondrías dentro de ese listado?
< br / >Archivos de configuracion innecesarios, archivos generados por el IDE (eclipse, Intellij)

 - ¿Se debería agregar la linea *.orig para evitar commitear los archivos generados por las mergetools? TIP: Github tiene publicado templates de gitignore para todos los lenguajes en github/gitignore
< br / >Sí, al agregar el asterisco adelante .gitignore considera todos los archvios con esa extensión.

- ¿Qué pasa si en vez de aplicar el comando git merge origin/master se aplica el comando git rebase origin/master? ¿Hay alguna diferencia en el código final? ¿Y la historia?
< br / > En el código no queda ninguna diferencia. La diferencia radica en la historia los commit, el merge a la hora de querer unificar realiza un commit de más. El rebase unifica sin necesidad de crear un nuevo commit
