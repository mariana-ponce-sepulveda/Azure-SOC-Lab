# Procedimiento de respuesta: incidente SSH

## 1. Objetivo
Establecer acciones para responder ante múltiples intentos
fallidos de autenticación SSH en un servidor Linux.

## 2. Análisis inicial
- Revisar los registros de autenticación.
- Identificar las direcciones IP de origen.
- Identificar las cuentas afectadas.
- Determinar la cantidad y frecuencia de los intentos.
- Comprobar si existieron accesos exitosos.

## 3. Contención
Si se confirma actividad maliciosa:
- Informar al responsable del sistema.
- Evaluar el bloqueo de la IP de origen.
- Aplicar las medidas autorizadas por el administrador.

## 4. Erradicación y recuperación
- Revisar las cuentas comprometidas.
- Cambiar credenciales si corresponde.
- Revisar la configuración del servicio SSH.
- Comprobar que el servidor funcione correctamente.

## 5. Documentación
Registrar:
- Fecha y hora del incidente.
- Evidencias encontradas.
- Sistemas y cuentas afectados.
- Acciones realizadas.
- Resultado de la respuesta.

## 6. Estado
Procedimiento propuesto con fines de aprendizaje.
No se ejecutaron acciones de bloqueo ni contención.
