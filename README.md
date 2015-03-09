# rankingfaker

Script para ascender maliciosamente en el ranking de github

Dicho de otro modo, como pone en el propio código:

> rankingfaker es una aplicación estúpida para hacer contribuciones espúrias en github (o en cualquier repo, claro)

## Adevertencia

**Aparta tus manazas de aquí: Ejecutar este script inconscientemente hará que se envíen (push) 10K de commits a este repositorio**

##Funcionamiento

Toma los números de un archivo (los dígitos de PI, en este caso) y los usa para crear un archivo de descripción del tipo "El 1 dígito de PI es tres.", añadiéndolos línea a línea y haciéndo un add y un commit cada vez.

Cada 1000 dígitos hace un push (porque el número máximo de contribuciones que github cuenta en un sólo push es 1000)

## Modo de Uso

Copia el fichero a un repositorio propio (clonarlo no sirve, porque los cambios sobre un repo clonado no cuentan como contribución) y ejecuta el script rankingfaker en ese mismo directorio.

10K contribuciones en un momento.

## Utilidad

Ascender ilegítimamente y de forma cómoda en el Top de usuarios de github de JJ merelo https://github.com/JJ/top-github-users-data
