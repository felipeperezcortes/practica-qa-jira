# Transferencia – Mensaje para monto inválido inconsistente

## Tipo de incidencia
Improvement

## Resumen
El mensaje mostrado para un monto de transferencia inválido no coincide con el texto definido por negocio.

## Steps to Reproduce
1. Iniciar sesión correctamente
2. Ir a la sección de Transferencias
3. Seleccionar una cuenta destino válida
4. Ingresar un monto menor al mínimo permitido (ejemplo: 999)
5. Hacer clic en el botón "Transferir"

## Expected Result
- La transferencia no se ejecuta
- El sistema muestra el mensaje: "El monto ingresado no es válido"

## Actual Result
- La transferencia no se ejecuta
- El sistema muestra el mensaje: "Monto incorrecto"

## Severity
Baja – no afecta la funcionalidad, solo la consistencia del mensaje.

## Priority
Baja – puede ser abordado como mejora de UX o consistencia.

## Notas
Reporte clasificado como improvement al cumplirse correctamente la regla funcional de negocio.
