# `02` Crea el script

En entornos GNU/Linux un script es un simple archivo de texto, que esta pensado para ser ejecutado por la terminal. Dicho de otra forma, cada una de las líneas del script se ejecutarán en la terminal como si alguien las transcribiera una a una.

Para ello podemos usar nano en la terminal o el editor de texto que tenemos en el menú de aplicaciones, lo importante es crear el archivo con las instrucciones que queremos que se ejecuten. 

Antes de probar tu script debes especificar que el archivo tiene permisos de ejecución y esta es una tarea para el usuario root.

## 📝 Instrucciones:

1. Crea un script que actualice la lista de paquetes disponibles y haga una actualización de todos ellos.

2. Asi como muchas otras, esta tarea habitualmente puede requerir confirmación del usuario. Para automatizar la actualización debes omitir la confirmación.

3. Debes ejecutar el script con privilegios de root.

## 💡 Pista:

> - Prueba ejecutar cada comando por separado antes de unir todo en el script
>
> - Casi todos los comandos tienen un manual integrado, solo escribe 'man' antes del comando y ve la documentación. Ejemplo 'man ls'