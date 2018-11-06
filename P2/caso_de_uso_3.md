## Modificar alumno
**ID**: 003

**Breve descripción:** El sistema permite modificar los alumnos

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**
1. El Apellido introducido no puede coincidir con ninguno existente, en caso de que coincida, el sistema pedirá el DNI.
2. El DNI introducido no puede coincidir con ninguno existente, en caso de que coincida, el sistema indicará un error.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere modificar un alumno.
2. El sistema muestra los datos actuales del alumno
3. El usuario modifica los datos

**Postcondiciones:**
* El sistema mostrará un mensaje de éxito con los nuevos datos si todo ha ido correctamente.

**Flujos alternativos:**  
 1.a. Si el alumno que se desea modificar el lider, el sistema mostrará un mensaje diciendo que dicho alumno es lider de un grupo
 3.a. Si los datos que se desean guardar coindicen con los de otro alumno, el sistema impedirá que se guarden esos datos y pedirá unos nuevos.
 
  
