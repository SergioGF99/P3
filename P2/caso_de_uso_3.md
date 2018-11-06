## Modificar alumno
**ID**: 003

**Breve descripción:** El sistema permite modificar los alumnos

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**
1. El DNI introducido no puede coincide con ninguno existente, el sistema indicará un error.
2. Si el Apellido introducido no coincide con ninguno existente, el sistema indicará un error.
3. Si el apellido está repetido, pedirá el DNI para modificar.
4. El alumno que se desea modificar 

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere modificar un alumno.
2. El muestra los datos actuales del alumno
3. El usuario modifica los datos

**Postcondiciones:**
* El sistema mostrará un mensaje de éxito con los nuevos datos si todo ha ido correctamente.

**Flujos alternativos:**  

  3.a. Si los datos que se desean guardar coindicen con los de otro alumno, el sistema impedirá que se guarden esos datos y pedirá unos nuevos.
