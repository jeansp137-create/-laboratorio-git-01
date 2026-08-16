# Guía de Contribución

¡Gracias por colaborar en este proyecto! Para mantener el código organizado y el historial de versiones limpio, sigue estas directrices:

## Flujo de Trabajo
1. Crea una rama descriptiva antes de trabajar (`feature/nueva-vista`, `fix/error-login`).
2. Realiza commits atómicos y frecuentes siguiendo la convención de mensajes.
3. Abre un **Pull Request** hacia la rama `main` explicando los cambios implementados.

## Estándar de Mensajes de Commit (Conventional Commits)
Todos los commits deben seguir la estructura:

`<tipo>(<alcance opcional>): <descripción corta en imperativo>`

### Tipos permitidos:
* `feat`: Nueva funcionalidad agregada al sistema.
* `fix`: Corrección de un error o bug.
* `docs`: Cambios exclusivos en documentación (README, manuales, etc.).
* `style`: Ajustes de formato, espaciado o indentación (sin cambios de lógica).
* `refactor`: Reestructuración de código sin agregar funciones ni corregir bugs.
* `chore`: Mantenimiento, archivos de configuración o dependencias (ej. `.gitignore`).
* `test`: Adición o modificación de pruebas.

### Ejemplos válidos:
* `feat(auth): implementa validacion de correo institucional`
* `docs(readme): actualiza lista de tecnologias del proyecto`
* `fix(parser): corrige lectura de archivos vacios`
