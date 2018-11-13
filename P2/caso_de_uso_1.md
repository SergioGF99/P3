## Añadir alumno
**ID**: 001

**Breve descripción:** El sistema permite añadir a un alumno

**Actores principales:** Profesores

**Actores secundarios:** Alumnos

**Precondiciones:**
1. El usuario debe tener datos que añadir de un alumno.

**Flujo principal:**
1. El caso de uso empieza cuando el usuario quiere introducir un nuevo alumno.
2. El sistema guarda los datos del nuevo alumno en el fichero binario.

**Postcondiciones:**
* Queda almacenada la información del nuevo alumno.

**Flujos alternativos:**  
1.a. Si introducimos un alumno categorizado como "líder" en un grupo que ya tiene un líder, el sistema mostrará un mensaje de error y redireccionará al usuario al menú principal.

1.b. Si introducimos un nuevo alumno cuando ya hay 150 alumnos, el sistema mostrará un mensaje de error, y redireccionará al usuario al menú principal.

2.a. Si el usuario no introduce nada en los campos equipo y lider, el sistema no mostrará ningun error, ya que esos campos son opcionales, por lo que redireccionará al usuario al menú principal.
