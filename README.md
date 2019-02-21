# Elimina archivos de slack desde línea de comandos
Elimina archivos viejos de slack (por default de 2 meses hacia atrás, pero es configurable).

Edita el archivo removeSlackOldFiles.php y añade tu token para que pueda funcionar. El token
se puede obtener de https://api.slack.com/web en el botón "Generate test tokens". Este token
debe bastar, no es necesario crear una aplicación pública.

Luego simplemente ejecuta el script, es necesario que tenga curl instalado (viene en muchas
instalaciones por default).

Para instalar curl (en el caso de que no se tenga), bastaría con:

    sudo apt install php-curl

El api de slack solo te devuelve 100 archivos por lo que será necesario si tienes muchos, 
ejecutar el script tantas veces como sea necesario.

Use el script bajo su propio riesgo.

https://www.elsiglodetorreon.com.mx/blogs/ToRo/2267-eliminar-archivos-viejos-slack-con-php
