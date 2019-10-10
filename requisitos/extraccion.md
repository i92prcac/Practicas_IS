# Práctica 2: Diseño e implementación de un software de gestión.

![N|Solid](https://www.uco.es/investigacion/proyectos/SEBASENet/images/Logo_UCO.png)

Por el grupo 36 y sus integrantes:

Carlos Prieto Cárdenas

Francisco Relaño Peña

# Requisitos del programa

Se ha llegado al acuerdo entre el Grupo de Prácticas 36 y la dirección de una consulta médica privada para que el primero se encargue de diseñar y construir un programa que se encargue de realizar la administración tanto de su personal como de su clientela.

Entre las principales acciones del programa, estarán:

Registrar datos relativos a los pacientes como:

* Las citas médicas a las cuales deban atender.
* Los tratamientos que estén siguiendo.
* Su historial médico.

A la hora de funcionar,  el programa deberá de ser capaz de leer y modificar los registros de sus clientes, así como crear nuevos para aquellos que se registren posteriormente. También deberá de distinguir entre las distintas entradas de sus clientes. Poseerá las capacidades de búsqueda y orden, de manera que el personal pueda buscar un elemento en específico de entre los pacientes de la manera más eficiente posible.

El programa también deberá de ser capaz de modificar o anular las citas asociadas con los clientes, y proponer una cita automática un mínimo de 6 meses después de la anterior o de la fecha en la que ha sido alterada.

Además, deberá de ser capaz de detectar errores de entre los siguientes posibles:

* Que tras realizar la búsqueda de un cliente en la base de datos éste no aparezca. Ante esta situación, el usuario podrá hacer dos cosas:
  - Podrá crear un nuevo registro para el cliente que no ha sido encontrado.
  - Podrá abortar la operación de búsqueda y volver al menú principal.
* Tiempo en el que ha seguido el tratamiento.
* Citas del paciente.
* Enlace hacia el historial clínico del paciente.

A su vez, el cliente desea que, al ordenar y buscar los registros asociados con los clientes, la operación se haga con el nombre.


# Datos

Los registros a almacenar sobre los pacientes deberán ser almacenados de manera separada en cada una de las siguientes categorías:

* DNI del paciente.
* Nombre completo del paciente.
* Dirección del paciente.
* Dirección postal del paciente.
* Teléfono del paciente.
* Condición de contrato del paciente con la clínica. Es decir:
  - Cliente de pago.
  - Cliente de seguro.
* Condición de tratamiento, definido como:
  - Tipo de tratamiento que sigue.
