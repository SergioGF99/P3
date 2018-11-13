### Buscar

**ID:** 002

**Breve descripción:** El sistema buscará datos.

**Actores principales:** Usuario/Profesor.

**Actores secundarios:** Alumnos.

**Precondiciones:**

1. El sistema debe tener datos en los que buscar.
2. El alumno debe existir en el sistema. 

**Flujo principal:**
1. El caso de uso empieza cuando el usuario vaya a buscar a un alumno.
2. El sistema busca los datos del alumno.

**Postcondiciones:**
* El sistema muestra un mensaje de éxito al encontrar en el sistema al alumno.

**Flujos alternativos:**

1.a. Si no hay datos en el sistema, el mismo mostrará un mensaje de error, y redireccionará al usuario al menú principal.

2.a. Si no existe el Alumno, el sistema mostrará un mensaje de error, y preguntará al usuario si quiere volver al menú principal o quiere buscar a otro alumno.
