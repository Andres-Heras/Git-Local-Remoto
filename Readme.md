GitHub es el host más grande para los repositorios de Git, y es el punto central de colaboración para millones de desarrolladores y proyectos.

En esta práctica vamos a comenzar a trabajar con repositorios locales, ya que Git nos permite trabajar de forma distribuida. En Git, al contrario que en los sistemas de versiones centralizados (Centralized Version Control Systems ó CVCSs), cada desarrollador puede contribuir con código a otros repositorios y mantener un repositorio público en el cual otros pueden basar su trabajo y en el que pueden contribuir.

En un proyecto en equipo cada uno de los desarrolladores tendrá su propio repositorio local copia del repositorio remoto. Hay que aclarar que cada mejora debe ir sobre una rama distinta, pero para facilitar esta práctica "git en local-remoto", siempre se trabajará sobre la rama máster.

Sigue los siguientes pasos y documéntalos con pantallazos en un documento pdf.

 1. Crea un nuevo repositorio en Github.
 2. Abre Git Bash en tu equipo local.  Te permitirá trabajar con git desde la línea de comandos.
 3. Cambia al directorio de tu proyecto local. (cd)
 4. Abre Git Bash en tu equipo local.  Te permitirá trabajar con git desde la línea de comandos.
 5. Cambia al directorio de tu proyecto local. (cd)6.Inicializa el directorio local como repositorio de git. (git init)
 6. Añade los ficheros a tu nuevo repositorio local (git add)(cd).Crea un index.html que contenga:
 
       - Nombre y apellidos del alumno
       - Usuario Github
       - Estas instrucciones de la tarea.
       
 7. Crea un commit de los ficheros añadidos (git commit)
 8. En Github, copia la url del repositorio remoto 
 9. En la línea de comandos de Git Bash, indica la url del repositorio remoto, para subir/sincronizar los cambios del repositorio local. (git remote add)
10. Confirma el cambio del repositorio remoto (git remote -v)
11. Sincroniza/sube los cambios del repositorio local a Github (git push)
