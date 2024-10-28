### 1. ¿Qué hacen los siguientes comandos?

- **pwd**: Muestra la ruta completa del directorio actual en el que estás trabajando. Es el acrónimo de "print working directory".

- **ls**: Lista los archivos y carpetas dentro del directorio actual. Si lo usas sin opciones, te mostrará solo los nombres visibles de los archivos.

- **cd**: Cambia el directorio de trabajo actual. Si lo usas con un nombre de carpeta o una ruta, te llevará a esa ubicación.

- **mkdir**: Crea un nuevo directorio (o carpeta) con el nombre que le des. Por ejemplo, `mkdir carpeta` creará una carpeta llamada "carpeta".

- **touch**: Crea un archivo vacío con el nombre que especifiques. También puede actualizar la fecha y hora de un archivo existente sin modificar su contenido.

### 2. Explicación de los comandos y argumentos en la línea de comandos

- **cd projects**: Cambias el directorio de trabajo al que se llama "projects". Si "projects" no existe, mostrará un error.

- **mkdir new-project**: Dentro del directorio "projects", creas una nueva carpeta llamada "new-project".

- **touch new-project/newfile.md**: Creas un archivo vacío llamado "newfile.md" dentro de la carpeta "new-project".

- **cd ..**: Subes un nivel en el sistema de archivos, regresando al directorio anterior al que estabas.

- **ls projects/new-project**: Listas el contenido del directorio "new-project" dentro de la carpeta "projects". En este caso, deberías ver "newfile.md" como el único archivo.

### 3. Comando para listar archivos, incluidos los ocultos, en un directorio de Linux o macOS

El comando a usar es `ls -a`:

- **ls**: Lista los archivos y carpetas en el directorio actual.

- **-a**: Es un parámetro que indica al comando que debe mostrar todos los archivos, incluidos los archivos ocultos. En Linux y macOS, los archivos cuyo nombre comienza con un punto (.) se consideran archivos ocultos (como `.bashrc`, `.gitignore`, etc.).



