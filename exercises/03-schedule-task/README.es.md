# `03` Programa la tarea

Una vez que ya tu script funcione correctamente puedes pasar al siguiente paso para automatizar su ejecución cada cierto tiempo. Para ello debes crear una tarea cron e indicar que ejecute el script de actualización todos los días.

## 📝 Instrucciones:

1. Crea una tarea cron que ejecute el script de actualización todos los días a la media noche.

2. Debe volcar la salida del script hacia el archivo `/var/log/actualizacion-servidor.log`

3. Debe volcar la salida de errores del script hacia el archivo `/var/log/actualizacion-servidor-error.log`

## 💡 Pista:

> El manual de crontab (tipea en la consola `man crontab`) no solo contiene información del comando en específico, sino también como funcionan todas las tareas programadas en general, puedes encontrar ahi muchas información útil.
>
> Recuerda que puedes usar los caracteres `>>` para redirigir la salida de un comando a un archivo, asi como `2>` para redirigir la salida de errores.
