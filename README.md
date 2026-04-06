# TP DSW


<img src="imagenes/UTN_logo.png" alt="Logo UTN" width="200">

<img src="imagenes/oscuro2.png" alt="Fondo Oscuro" width="500">
Status: draft

Propuesta de Trabajo Práctico

Descripción
La propuesta de nuestro trabajo consiste en desarrollar un sistema que permita la gestión de alquileres de canchas de distintos deportes. Los Clientes podrán visualizar los turnos disponibles y realizar reservas sobre los mismos. Además, el Encargado podrá gestionar las canchas que tenga asignadas. Finalmente, el Dueño podrá acceder a distintas métricas relevantes para analizar el rendimiento de su negocio.

Modelo

<img src="imagenes/oscuro2.png" alt="Fondo Oscuro" width="500">

Alcance

| Requerimiento | Detalle |
| :--- | :--- |
| **CRUD Simple** | 1. CRUD Cliente <br> 2. CRUD Encargado cancha <br> 3. CRUD Dueño de cancha <br> 4. CRUD Turno <br> 5. CRUD Tipo de cancha <br> 6. CRUD Tipo de turno |
| **CRUD Dependiente** | 1. CRUD Localidad {depende de} CRUD Provincia <br> 2. CRUD Cancha {depende de} CRUD Complejo |
| **Listado + detalle** | 1. Listado de complejos que poseen turnos disponibles en un determinado horario para un deporte. <br> 2. Listado de turnos realizados por complejo + detalle <br> 3. Listado de turnos reservados diarios. <br> 4. Listado de recaudación diario durante un mes por complejo |
| **CUU/Epic** | 1. Reservar un turno de una cancha en un horario <br> 2. Cancelar un turno <br> 3. Registrarse como cliente <br> 4. Dar de alta cuenta de dueño de complejo <br> 5. Enviar recordatorio de turno previo a su realización <br> 6. Recuperar contraseña |


