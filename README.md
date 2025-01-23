# Ciclos de Vida Laboratorio 1


## Bienvenidos al laboratorio 1 de Ciclos de vida de software
Para este laboratorio aprenderemos crear un Readme y a añadirlos  un repositorio creado por nosotros, haremos tambien nuestros primeros trabajos en equipo sobre un mismo repositorio.

# Parte I

## ¿Para que sirve el comando "git add"?
Prepara los cambios realizados en la maquina local o zona de trabajo en el repositorio.

## ¿Para que sirve el comando "git commit -m"?
Un commit sirve para guardar los cambios realizados en el area de trabajo añadidos previamente al historial el repositorio
el **-m** es utilizado para añadir un mensaje a este "punto de guardado".

## Elaboracion del README

![README](images/ElaboracionRME.png)

## Cuenta de Github enlazada al correo institucional

![correo](images/CorreoVinculado.png)

# Parte II

## 1. Definir el Owner y el Colaborador 
- Owner: Juan Andrés Rodríguez (Juan_Rpenuela)
- Colaborator: Nicolás Pachón

## 2. Invitación del Owner al Colaborador

![Invitation](images/Invitacion.png)	

## 3. Invitación via teams

![InvitationTeams](images/InvitacionTeams.png)
 
## 4. El colaborador acepta la invitacion al repositorio

![Invitation](images/Invitacion2.png)



## 5. Owner y colaborador intentan cambiar el readme a la vez

![Invitation](images/problemasDeMerge.png)

## 6. ¿Que sucedió?
Uno de los dos colaboradores del repositorio logró subir sus cambios, el otro no lo logró dando el problema de que los archivos en el repositorio tienen cambios los cuales no se tienen en la maquina local en la que se trabaja, tambien nos pide que hagamos un pull sobre el repositorio.

## 7. Intento de pull y resolución de conflictos manuales
Al intentar hacer el pull del repositorio las persona que no logro subir sus cambios, aparece otro problema debido al contenido que se hizo en un archivo del repositorio antes de hacer el pull, por lo que si no se hace el merge automatico, debemos hacerlo nosotros manualmente

![Invitation](images/Problemas2.png)

## 8. Resolución de conflictos IntelliJ
Procedemos a crear un conflicto y a solucionarlo con intellij


# Parte III

## 1.  ¿Hay una mejor forma de trabajar con git para no tener conflictos?
Una forma recomendada para trabajar en github es haciendo el uso de ramas, puesto que este permite hacer cambios y demás acciones en un ambiente aislado con respecto a la rama principal, generando que se pueda editar codigo y agregarlo sin interferir con los cambios generados por otras personas o colaboradores.
## 2.  ¿Qué es y como funciona el  **Pull Request**?
El pull request, como el nombre indica, es una solicitud que se realiza para poder subir a un repositorio los avances o modificaciones realizadas en una rama en especifico. Esta se solicita y una persona encargada debe revisar los archivos asociados al commit para decidir si integrar o no los cambios a una rama.
## 3.  Creen una rama cada uno y suban sus cambios