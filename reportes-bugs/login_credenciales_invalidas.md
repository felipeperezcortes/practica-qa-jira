# Login – Credenciales inválidas

## Tipo de incidencia
Bug

## Resumen
El sistema no muestra de forma persistente el mensaje de error al ingresar credenciales inválidas en la pantalla de login.

## Steps to Reproduce
1. Ir a la página de Login
2. Ingresar un email válido
3. Ingresar una contraseña incorrecta
4. Hacer clic en el botón "Ingresar"

## Expected Result
El sistema debería mostrar un mensaje de error claro indicando que el usuario o la contraseña son incorrectos, manteniéndolo visible para el usuario.

## Actual Result
El mensaje de error se muestra brevemente y desaparece automáticamente después de unos segundos, sin dejar feedback visible para el usuario.

## Severity
Media – afecta la experiencia de usuario, pero no bloquea el acceso al sistema.

## Priority
Alta – el login es un flujo crítico y requiere feedback claro para el usuario.

## Notas
Incidencia documentada y gestionada en Jira, incluyendo retesting posterior al fix.
