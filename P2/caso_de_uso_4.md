## Eliminar alumno
**ID**: 004

**Breve descripción:** El sistema permite eliminar a un alumno

**Actores principales:** Profesores

**Actores secundarios:** Alumnos


**Precondiciones:**
1. Se deberá pedir el apellido o DNI para identificar al alumno que se quiere eliminar.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario/profesor quiere eliminar un alumno.
2. El sistema elimina al usuario deseado de la base de datos.

**Postcondiciones:**
1. El sistema mostrará un mensaje de éxito en el caso de que se haya eliminado correctamente.
2. Se actualizarán los datos en el fichero binario.

**Flujos alternativos:**  
1.a. Si se desea eliminar por apellido y hay varios alumnos con el mismo apellido, el sistema automaticamente pedirá el DNI del alumno que concreto que se desea eliminar
2.a. Si el alumno que se desea eliminar es lider de un grupo, el sistema mostrará un mensaje de advertencia indicando que el grupo al que pertenecia ya no tiene lider, pero no dará ningún error.
