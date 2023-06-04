# Script de respaldo y restauración

Este script de Bash proporciona un menú interactivo para realizar respaldos y restaurar respaldos de directorios.

## Uso

1. Asegúrate de tener Bash instalado en tu sistema.

2. Descarga el archivo `respaldo_restauracion.sh`.

3. Abre una terminal y navega hasta la ubicación donde se encuentra el archivo descargado.

4. Ejecuta el siguiente comando:

   ```bash
   bash respaldo_restauracion.sh
    Sigue las instrucciones en el menú para realizar respaldos o restaurar respaldos.

Descripción del script

El script consta de las siguientes partes:

    mostrar_menu(): Muestra el menú de opciones disponibles.
    realizar_respaldo(): Permite realizar un respaldo de un directorio especificado.
    restaurar_respaldo(): Permite restaurar un respaldo desde un archivo especificado en un directorio destino.
    ejecutar_script(): Ejecuta el script en un bucle continuo hasta que se seleccione la opción de salida.

El menú proporciona las siguientes opciones:

    Realizar respaldo: Permite especificar un directorio de origen y un directorio de destino para crear un archivo de respaldo comprimido.
    Restaurar respaldo: Permite especificar un archivo de respaldo y un directorio de destino para extraer el contenido del respaldo en el directorio destino.
    Salir: Permite salir del script.

El respaldo se crea utilizando el comando tar para comprimir y excluir directorios especificados en el archivo de respaldo. La restauración se realiza extrayendo el contenido del archivo de respaldo utilizando el comando tar.

El script verifica si las operaciones de respaldo y restauración se realizan correctamente y muestra mensajes de éxito o error correspondientes.

¡Utilízalo con responsabilidad!
