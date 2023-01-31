---
title: "Comandos básicos macOS 🐧🍎"
date: 2023-01-31T09:51:32+01:00
draft: false
tags: [MacOs, Entrada]
---
Si eres un usuario de Mac, es posible que ya conozcas la mayoría de las funciones y aplicaciones básicas que se incluyen con el sistema operativo. Sin embargo, hay una herramienta poderosa que muchos usuarios no conocen: los comandos de la terminal.

La terminal es una interfaz de línea de comandos que te permite interactuar con tu Mac de una manera más avanzada. Con los comandos de terminal, puedes realizar tareas que normalmente no están disponibles en el Finder o en las aplicaciones gráficas, como mostrar archivos ocultos, copiar y mover archivos en masa, e incluso hacer que tu Mac hable. Desde los comandos básicos hasta algunos trucos más avanzados, cubriremos todo lo que necesitas saber para sacar el máximo provecho de la terminal en tu Mac.

## Aquí hay algunos comandos básicos para macOS:
- **"ls"** - Muestra una lista de los archivos y carpetas en el directorio actual.

- **"cd"** - Cambia a un directorio específico. Por ejemplo, "cd Documents" cambia al directorio de Documentos.

- **"pwd"** - Muestra la ruta completa del directorio actual.

- **"mkdir"** - Crea un nuevo directorio. Por ejemplo, "mkdir nueva_carpeta" crea una nueva carpeta llamada "nueva_carpeta".

- **"touch"** - Crea un nuevo archivo. Por ejemplo, "touch nuevo_archivo.txt" crea un nuevo archivo de texto llamado "nuevo_archivo.txt".

- **"rm"** - Elimina un archivo o una carpeta. Por ejemplo, "rm archivo.txt" elimina el archivo "archivo.txt".

- **"cp"** - Copia un archivo o una carpeta. Por ejemplo, "cp archivo.txt copia_archivo.txt" copia el archivo "archivo.txt" como "copia_archivo.txt".

- **"mv"** - Mueve o renombra un archivo o una carpeta. Por ejemplo, "mv archivo.txt nuevo_nombre.txt" renombra el archivo "archivo.txt" como "nuevo_nombre.txt".

Estos son algunos comandos básicos que pueden ser útiles para el uso diario de la línea de comandos en macOS, que tambien encontramos en todas las distribuciones de Linux. Sin embargo, macOS presenta gran variedad de comandos unicos para su sistema, tales como:

- **"open"** - Abre un archivo o una carpeta con la aplicación predeterminada. Por ejemplo, "open imagen.png" abre la imagen "imagen.png" con la aplicación de imagen predeterminada.
    - Abrir una carpeta: "open ~/Desktop/MiCarpeta"
    - Abrir un archivo: "open ~/Documentos/MiArchivo.txt"

- **"screencapture"** - Captura una imagen de la pantalla. Por ejemplo, "screencapture -iW capture.png" captura una imagen de la pantalla y la guarda como "capture.png".
    - Capturar la pantalla completa y guardarla en el escritorio: "screencapture ~/Desktop/captura.png"
    - Capturar una selección y guardarla en el escritorio: "screencapture -i ~/Desktop/captura.png"

- **"ditto"** - Copia archivos y carpetas con opciones avanzadas de formato. Por ejemplo, "ditto -rsrcFork carpeta_original carpeta_destino" copia la carpeta "carpeta_original" a "carpeta_destino" con opciones adicionales de formato.
    - Copiar una carpeta: "ditto ~/Desktop/MiCarpeta ~/Documentos/MiCarpetaCopiada"
    - Copiar un archivo: "ditto ~/Documentos/MiArchivo.txt ~/Escritorio/MiArchivoCopiado.txt"

- **"say"** - Hace que el sintetizador de voz de macOS hable un texto específico. Por ejemplo, "say Hola, mundo" hace que el sintetizador de voz diga "Hola, mundo".
    - Hacer que el sintetizador de voz hable un texto: "say Hola, mundo"

- **"defaults"** - Cambia las opciones predeterminadas del sistema. Por ejemplo, "defaults write com.apple.finder AppleShowAllFiles YES" muestra todos los archivos ocultos en el Finder.
    - Mostrar archivos ocultos en el Finder: "defaults write com.apple.finder AppleShowAllFiles YES"
    - Ocultar archivos ocultos en el Finder: "defaults write com.apple.finder AppleShowAllFiles NO"

Estos son algunos ejemplos de cómo se pueden utilizar los comandos únicos en macOS. Hay muchas otras opciones y configuraciones disponibles para cada comando, por lo que es posible realizar una amplia variedad de tareas.