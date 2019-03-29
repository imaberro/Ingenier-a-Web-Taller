# Glosario


Este glosario hablará sobre algunos términos y comandos que pertenecen a Git.


### Control de versiones (VC)
Es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas recuperar versiones específicas más adelante.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones "Git")

### Control de versiones distribuido (DVC)
Aquí los clientes no solo descargan la última instantánea de los archivos, si no que replican completamente el repositorio. Es donde entran los sistemas de control de versiones distribuidos.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Empezando-Acerca-del-control-de-versiones "Git")

### Repositorio remoto y Repositorio local
Los repositorios remotos son versiones locales del proyecto en el cual se estará trabajando los cuales se encuentran alojados en Internet o en algún punto de la red. Mientras que los repositorios locales a diferencia de los remotos son aquellas versiones del proyecto que se encuentran en tu computadora.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Trabajando-con-repositorios-remotos "Git")

### Copia de trabajo / Working Copy
Todos los archivos, incluyendo versiones anteriores, sse encuentran en un repositorio. Ahi, todos los cambios que han sido hechos en el repositorio anteriormente estarán siempre disponibles. 
[Referencia bibliográfica](https://www.thomas-krenn.com/en/wiki/Git_Basic_Terms "Thomas Krenn")

### Área de preparación / Staging Area
Es una carpeta que generalmente está contenido en el directorio de Git, que almacena información acerca de lo que va a ir a tu próximo commit.
[Referencia bibliográfica](https://www.atlassian.com/git/tutorials/saving-changes "Atlassian")

### Preparar Cambios / Stage Changes
Es una etapa donde se preparan los cambios que se desean realizar al proyecto, utilizando el comando add para agregar estos cambios.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio "Git")

### Confirmar cambios / Commit Changes 
El la última estapa del ciclo, en esta se confirman todos los cambios que se hayan preparado en el repositorio local.
[Git](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Guardando-cambios-en-el-repositorio "Git")

### Commit
El comando "commit" se usa para guardar los cambios en el repositorio local.
[Referencia bibliográfica](https://www.git-tower.com/learn/git/commands/git-commit "Git Tower")

### clone 
El comando clone sirve para tener una copia de un repositorio Git existente, este comando crea un nuevo directorio, entra en él y lo deja como un repositorio vacío de Git y finalmente añade uno remoto de la dirección URL que se le pasa, de esta forma se consigue una copia de los repositorios remotos.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Fundamentos-de-Git-Obteniendo-un-repositorio-Git "Git")

### pull
El comando pull es abreviación de los comandos fetch y merge, este incorpora cambios desde un repositorio remoto al branch o rama actual, es decir, actualizas tu repositorio local con el repositorio remoto.
[Referencia bibliográfica](https://es.stackoverflow.com/questions/245/cu%C3%A1l-es-la-diferencia-entre-pull-y-fetch-en-git "Stackoverflow")

### push
Este comando se encarga de actualizar los repositorios remotos con los repositorios locales que fueron modificados y guardados con "add" y "commit".
[Referencia bibliográfica](https://git-scm.com/docs/git-push "Git")

### fetch 
El comando fetch trae los cambios, pero a diferencia del comando pull, este los deja en otro branch hasta que se hace el merge.
[Referencia bibliográfica](https://es.stackoverflow.com/questions/245/cu%C3%A1l-es-la-diferencia-entre-pull-y-fetch-en-git "Stackoverflow")

### merge
El comando *git merge* viene justo después del comando fetch, y sirve para traer los cambios que se habían marcado con fetch al branch local.
[Referencia bibliográfica](https://es.stackoverflow.com/questions/245/cu%C3%A1l-es-la-diferencia-entre-pull-y-fetch-en-git "Stackoverflow")

### status
Este comando es utilizado para mostrar el estado del proyecto y los cambios que se le han realizado.
[Referencia bibliográfica](https://git-scm.com/docs/git-status "Git")

### log
El comando *git log* es utilizado para obtener el id de un "commit".
[Referencia bibliográfica](https://git-scm.com/docs/git-log "Git")

### checkout
El comando *git checkout* sirve para reemplazar cambios locales, en caso de haber cometido un error.
[Referencia bibliográfica](https://git-scm.com/docs/git-checkout "Git")

### Rama / Branch
Las ramas o *Branch's* son utilizadas para desarrollar funcionalidades aisladas unas de otras. La rama master es la rama "por defecto" cuando creas un repositorio.
[Referencia bibliográfica](https://git-scm.com/book/es/v1/Ramificaciones-en-Git-%C2%BFQu%C3%A9-es-una-rama%3F "Git")

### Etiqueta / Tag
Las etiquetas se recomiendan para cada nueva version publicada de un software. Es el nombre de la version.
[Referencia bibliográfica](https://www.atlassian.com/git/tutorials/inspecting-a-repository/git-tag "Atlassian")

