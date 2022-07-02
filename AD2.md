# Actividad Dirigida 2 #  
A continuación describo como fue el proceso para realizar la **Actividad Dirigida 2**  
- como primer paso convertí los archivos de markdown en html. Luego fui a https://github.com/nebrijas/csaldanag-web/settings/pages
- Elegí en Source en la opción 1: main y en la opción 2: root.
- Luego creé un nuevo archivo desde la web (con Add file) llamdo ad2.md (que es el documento actual).

- Los siguientes cambios se realizcé en local, para ello hay que descargué **Git Bash** y posteriormente abrí la aplicación para acceder a la terminal.

- Primero escribí **pwd** y dí enter para ver en que directorio nos estaba ubicado.

- Luego escribí **git clone** [enlace](https://github.com/nebrijas/Csaldanag-web) y dí enter para copiar el directorio de mi repositorio al directorio local del ordenador.

- Ya creada la carpeta en nuestro directorio, se puede vizualizar con **ls** y luego enter.

- Para ingrear a la carpeta utilizamos el comando cd y el nombre de la carpeta, en mi caso **cd Csaldanag-web** y damos enter.

- Ahora que estamos en el interior de la carpeta, podemos usar **ls** y enter para vizualizar el contenido que se encuentra en su interior.

- Luego escribimos **git config user.name**, seguido de nuestro nombre de usuario de **GitHub** y damos enter.

- Escribimos **git config user.email**, seguido del correo que se utiliza en GitHub y damos enter.

- En el navegador vamos a la web: **https://github.com/settings/tokens**

- Elegí **Generate new token** y le damos el nombre en Note que queramos. En expiration le modificamos la fecha de expiración a 60 días. En select scopes elegimos **Repo** para que se activen todas las casillas de repo. Las demás casillas se dejan sin seleccionar. Poste>

- Copiamos el token que se ha creado.

- Retornamos a **Git Bash** y escribimos **echo** dentro el token copiado previamente> ../.token para añadir un archivo oculto en la carpeta superior del árbol con el token que acabamos de copiar impreso.

- Escribí **README.md ad1.md** y damos enter para copiar el contenido de **README.md** a una nueva carpeta de nombre **ad1.md**.

- Luego escribí nano README.md y damos enter. Al abrirse la consola de nano para editar el archivo poniéndole un título y dos enlaces, uno a **ad1.md** y otro a este directorio **ad2.md**.

- Escribimos **git status** y damos enter. Para ver las modificaciones realizadas.

- La nueva carpeta que no existía o está modificada aparece como sin trackear y para que esté online hay que escribir **git add** seguido del nombre de la carpeta y dar enter.

- Luego escribimos **git commit -m "modifico README.md y añado ad1.md"** y damos enter, para escribir el comentario explicativo de los cambios realizados.

- Escribimos **git push** y damos enter para guardar el contenido en **GitHub**.

- Comprobamos que ahora ya aparece la nueva carpeta online.
