# Búsquedas, el libro

Búsquedas es la traducción al castellano de Searches, un libro que recopila las búsquedas realizadas con Google. Es como un diario que no sabías que ya estabas escribiendo.
Más información en el proyecto original: [ishback.com/searches](ishback.com/searches)

## Crea tu propio libro Búsquedas:

### Descarga tu historial de búsquedas

1. Ve a [https://history.google.com](https://history.google.com). Necesitarás introducir tu email de Google y tu contraseña si aún no estás logueado.
2. En la sección 'Actividad en la Web y en Aplicaciones', haz clic en el icono con los tres puntos en la esquina superior derecha y pulsa en 'Descargar búsquedas'.
3. Pulsa el botón ‘Crear Archivo’. Recibirás un correo electrónico cuando el historial esté listo para ser descargado.
4. Descomprime el archivo ZIP. Deberás obtener un carpeta llamada 'Búsquedas' que contiene un archivo index.html y otra carpeta llamada 'Búsquedas'.

### Descarga DrawBot

Este libro está generado con DrawBot, una aplicación gratuita para Mac.

5. Para descargar DrawBot, ve a [http://www.drawbot.com/content/download.html](http://www.drawbot.com/content/download.html).

### Descarga el script busquedas.py

busquedas.py es un script en python que extrae tus búsquedas y crea un libro.

6. Descarga busquedas.py de este repositorio.
7. Mueve busquedas.py a la carpeta 'Búsquedas' que obtuviste al descomprimir el archivo ZIP (la carpeta en la que se encuentra el archivo index.html).

### Genera el libro

8. Abre busquedas.py con DrawBot. Pulsa ⌘+R para ejecutar el script. El libro aparecerá en el panel izquierdo de DrawBot.
9. Para guardar el libro en formatoPDF, ve a File > Save PDF. También puedes imprimir el libro directamente desde DrawBot (File > Print…).

Por defecto, el script genera un libro para tus búsquedas de 2015. Si deseas crear un libro de un año anterior cambia el año en la línea 6 del script.
