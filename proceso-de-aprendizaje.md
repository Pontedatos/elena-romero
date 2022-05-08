# DOCUMENTACIÓN DEL PROCESO DE APRENDIZAJE
En la asignatura Periodismo de Datos el objetivo principal se ha puesto en conocer nuestro ordenador para saber con qué herramienta trabajamos cuando trabajamos con datos. Por este motivo, desde el primer momento las prácticas no han ido tanto enfocadas al ejercicio del Periodismo de Datos como tal, sino al conocimiento de nuestro ordenador. Para ello, hemos realizado distintas actividades: 

### Trabajo desde la terminal 
En primer lugar, los que como es mi caso contamos con un ordenador Windows, nos instalamos el subsistema [**WSL**](https://docs.microsoft.com/es-es/windows/wsl/about) para "poder ejecutar un entorno de GNU/Linux". 
Sin embargo, la herramienta de trabajo principal de este curso ha sido **Ubuntu**, "una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto", que obtuvimos de este [enlace](https://ubuntu.com/download). 
Para ello, tuvimos que ejecutar en la [**PowerShell**](https://docs.microsoft.com/es-es/powershell/scripting/overview?view=powershell-7.2) (una solución de automatización de tareas multiplataforma formada por un shell de línea de comandos, un lenguaje de scripting y un marco de administración de configuración) de Windows el comando `wsl --install -d Ubuntu`, para poder así completar el proceso de instalación de Ubuntu. 

### Cywin
Después de un tiempo trabajando desde Ubuntu, pasamos a emplear [**Cywin**](https://www.cygwin.com/), una gran colección de herramientas GNU y de código abierto que proporcionan una funcionalidad similar a la de una distribución de Linux en Windows.
Tras un proceso de instalación en el ordenador seguido en clase, procedimos a configurar la cuenta de GitHub en la terminal. Este proceso ya se había realizado previamente en Ubuntu para subir prácticas anteriores a este cambio, por eso su ejecución fue familiar: 
- `git config --global user.name elenaromvar`
- `git config --global user.name` *la terminal devuelve el nombre de usuario puesto anteriormente, eso nos confirma que se ha realizado con éxito*
- `git config --global email 100386306@alumnos.uc3m.es`
- `git config --global email` *igual que en el paso anterio*
* Cabe destacar que en el proceso de elaboración de las prácticas de este curso, pese a la recomendación del profesor de trabajar desde Cywin, por una serie de complicaciones que me imposibilitaban el desarrollo de dichos trabajos, mis prácticas han sido elaboradas utilizando Ubuntu, plataforma empleada a principio de curso. 

### Jupyter
Las últimas dos prácticas del curso se han realizado en *notebooks* de [**Jupyter**](https://jupyterhub.uc3m.es/hub/login), al cual hemos podido acceder gracias a ser alumnos de la UC3M. En Jupyter hemos creado varios *notebooks* en los que hemos hecho desde pruebas hasta prácticas completas, empleando los lenguages de programación **R** y **Python 3**. Gracias a ellos hemos podido instalarnos librerías con las que trabajar, empleando códigos que han ejecutado desde un gráfico lineal a un mapa de puntos, y a los que hemos podido completar con comentarios en lenguaje **Markdown**, que es el mismo que utilizamos en este y otros archivos de GitHub.

### Comandos
Si algo ha sido crucial en el aprendizaje y desarrollo de esta asignatura, esto ha sido el uso de los comandos. Para realizar cualquier paso, para subir cualquier trabajo, editar cualquier texto o configurar cualquier cosa que fuese pertinente, hemos tenido que recurrir a ellos conforme nos iba indicando el profesor. 
A continuación, detallo una lista de los más importantes y su función: 
- `pwd`: indica dónde nos encontramos
- `cd`: cambia el directorio (la ubicación en la que estamos)
- `ls`: muestra qué hay dentro del directorio en el que nos encontramos (listar)
- `echo`: impresión de un texto en pantalla
- `cp`: sive para copiar elementos
- `mv`: sirve para mover archivos de un punto a otro del ordenador 
- `nano`: editor de textos
- `cat`: concatenar 
- `mkdir`: crear un nuevo directorio
- `df`: obtener un dataframe
- `head` / `tail`: muestra el principio y el final de una lista 
- `touch`: crea un archivo en blanco
- `git init`: crea un nuevo repositorio de Git, y también dota de las propiedades de éste a una carpeta ya creada
- `git clone`: clona carpetas
- `git add`: añade elementos del ordenador al repositorio de GitHub
- `git status`: indica el estado del directorio de trabajo
- `git commit`: captura los cambios preparados en el proyecyo
- `git pull`: descarga contenidos de un repositorio remoto y actualiza el repositorio local
- `git push`: subir los archivos ya comiteados desde la terminal a GitHub
