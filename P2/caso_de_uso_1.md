## Añadir alumno
**ID**: 001

**Breve descripción:** El sistema permite añadir a un alumno

**Actores principales:** Profesores

**Actores secundarios:** Alumnos

**Precondiciones:**
1. Si el DNI o el correo del nuevo alumnno introducido coinciden con uno ya existente, el sistema indicará un error.
2. Si queremos introducir un alumno que sea lider en un grupo en el que ya hay un lider, el sistema mostrará un error.
3. Si ya hay 150 alumnos en el sistema y se quieren añadir más, el sistema mostrará un error

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere introducir un nuevo alumno.
2. El sistema guarda los datos del nuevo alumno en el fichero binario.

**Postcondiciones:**
* El sistema mostrará un mensaje de éxito si todo ha ido correctamente.

**Flujos alternativos:**  
2.a. Si el usuario no introduce nada en los campos equipo y lider, el sistema no mostrará ningun error, ya que esos campos son opcionales.
