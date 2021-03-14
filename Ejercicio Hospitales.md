<h2>Ejercicio Hospitales</h2>
En la construcción de un sistema de información para el control hospitalario se relevaron los siguientes conceptos:

Hospital, con los datos nombre, dirección y teléfono.
Sala, con los datos número y cantidad de camas.
Médico, con los datos cédula de identidad, nombre y especialidad.
Paciente, con los datos cédula de identidad, nombre, dirección y fecha de nacimiento.
Por otra parte, las relaciones relevadas entre dichos conceptos son:

Cada hospital tiene varias salas. Todas y cada una de ellas pertenecen a un hospital (y solo a uno).
Cada médico trabaja en un único hospital. Todo hospital tiene al menos 10 médicos.
Un paciente puede estar internado; si lo está, estará en una sala (y sólo en una).
La capacidad máxima de camas que puede tener una sala es de cinco pacientes.
Cada paciente puede ser atendido por más de un médico (pero por lo menos por uno), y a su vez cada médico puede atender varios pacientes.
Construir el Modelo de Dominio correspondiente
