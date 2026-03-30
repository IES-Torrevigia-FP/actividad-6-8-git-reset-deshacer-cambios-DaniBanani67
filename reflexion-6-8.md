# Reflexión Actividad 6.8

## Diferencias

--soft: deshace el commit pero deja los cambios en staging

mixed: deshace el commit y saca los cambios del staging, pero los archivos se quedan modificados

--hard: deshace el commit y borra todos los cambios

## Reset vs revert

reset cambia el historial, por eso se usa mas en local
revert crea un commit nuevo que deshace otro, por eso es mas seguro en ramas compartidas.

## Cuándo usar cada uno

soft: cuando quieres rehacer un commit

mixed: cuando quieres revisar cambios antes de volver a hacer commit

hard: para borrar cambios que no quieres conservar en un entorno de prueba