## Modificar alumno
**ID**: 003

**Breve descripción:** El sistema permite modificar los alumnos

**Actores principales:** Profesor

**Actores secundarios:** Alumno

**Precondiciones:**
1. El Apellido introducido no puede coincidir con ninguno existente.
2. El DNI introducido no puede coincidir con ninguno existente.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere modificar un alumno.
2. El sistema muestra los datos actuales del alumno
3. El usuario modifica los datos

**Postcondiciones:**
* El sistema mostrará un mensaje de éxito con los nuevos datos si todo ha ido correctamente.

**Flujos alternativos:**  
 3.a. Si se quiere buscar por apellidos, y los apellidos introducidos son únicos, el sistema permitirá modificar los datos. En caso de que coincidan, se pedirá el DNI.
 
 3.b. Si el DNI que se desean modificar coindice con el de otro alumno, el sistema impedirá que se guarden esos datos mostrando un error y pedirá unos datos nuevos.
 
 3.c. Si el alumno que se desea modificar es el lider, el sistema mostrará un mensaje diciendo que el alumno que se está modificando es lider.
 
 3.d Si un alumno que no era lider se modifica para que lo sea y en ese grupo y hay un lider, se mostrará un mensaje indicando si quiere que se sustituya el lider actual.
