# Proyecto

# Objetivo 
El objetivo es estructurar un hotel. En este hotel se plantea la existencia de las clases:
Hotel: encargado de gestionar las habitaciones, empleados y clientes
Personas: clase madre de empleados y clientes
Empleados: pueden hacer reservas con descuento
Clientes: personas que harán las reservas de las habitaciones
Habitaciones: Podrán ser reservadas, se puede hacer varias reservas al mismo cuarto con el objetivo de poder apartarlos a lo largo del tiempo (ej: una de 18 al 24 y la otora reserva del 28 al 31)
Reserva: manejo de las reservaciones de las habitaciones

# Consideraciones
Casos de error: Empalmamiento de las reservas, se debe checar disponibilidad antes de reservar porque el programa no es capaz de evitar empalmamientos.

El programa solo corre en la consola y esta hecho con c++ standard por lo que corre en todos los sistemas operativos
compilar con: "g++ personas.h reserva.h hotel.h habitacion.h main.cpp"
correr en linux: "/a.out"
correr en windows: "a.exe

# Versiones
Versión 1: Se agregó el UML para plantear la base. Se agregó link al proyecto anterior.

Versón 2: Comienzo desde cero. Se agregó UML nueva y primer archivo de herencias, con las clases cliente y empleado de la clase madre personas.

Versión 3: Se agregaron mas clases y el main. Actualización de UML.

Versión 4: Se agregó el main completo y se modificaron todas las clases para adpatarse a los requerimientos, se actualizo el UML.
