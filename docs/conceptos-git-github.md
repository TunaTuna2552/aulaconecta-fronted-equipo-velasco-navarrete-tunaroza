Comprobación conceptual
1. ¿Qué puede hacer Git aunque GitHub no exista? - Git puede almacenar versiones de un proyecto, github es como para acceder a estas versiones

2. ¿Por qué una rama reduce el riesgo de dañar main? - Por que una rama olo edita una versión alterna, sin dañar o mover el código principal

3. ¿Qué diferencia existe entre guardar un archivo y crear un commit? - Guadar actualiza el archivo permanentemente mientras que el commit es un registro de cambios.

4. ¿Por qué un pull request no es lo mismo que un merge? - Pul request es la solicitud de revisión de una rama para saber si debe ser integrada a otra mientras que merge es la integración ya revisada y aceptada de una rama en otra.

5. ¿Qué evidencia permite saber quién cambió algo y por qué? - Los commits permiten saber quién cambió algo y el por qué, ya que al ser un registro de cambios o versiones registran el autor, la fecha y un mensaje del propósito de la edición o lo que se cambió

## Reto rápido de secuencia
1. Crear repositorio
- Primero se crea el repositorio para guardar todos los archivos del proyecto en un mismo lugar. Así se evita que cada integrante tenga versiones diferentes del trabajo.

3. Crear rama
- Después se crea una rama para trabajar sin modificar la rama principal (main). Así, si ocurre algún error, la versión principal del proyecto no se ve afectada.

3. Hacer commits
- Luego se realizan los commits para guardar los cambios que se van haciendo. Esto permite llevar un historial y saber qué se modificó en cada momento.

4. Abrir Pull Request
- Cuando el trabajo está listo, se abre un Pull Request para que otra persona revise los cambios antes de agregarlos a la rama principal. Esto ayuda a encontrar errores antes de hacer el Merge.

5. Revisar
- El revisor revisa los cambios y verifica que todo esté correcto. Así se pueden detectar errores o cosas que se puedan mejorar.

6. Corregir observaciones
- Si el revisor encuentra algún problema, se hacen las correcciones necesarias antes de unir los cambios con la rama principal. Esto ayuda a que el trabajo quede mejor.

7. Fusionar
- Cuando todo está revisado y aprobado, se hace el Merge para pasar los cambios a la rama main. De esta forma, la rama principal solo tendrá cambios que ya fueron revisados.
