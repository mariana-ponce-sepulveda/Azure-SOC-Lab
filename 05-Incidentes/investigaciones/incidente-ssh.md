# Investigación de incidente: intentos fallidos de SSH

## 1. Descripción del incidente
Se plantea un escenario simulado en el que un servidor Linux
presenta múltiples intentos fallidos de autenticación mediante SSH.

## 2. Objetivo de la investigación
Identificar posibles intentos de acceso no autorizado y analizar
los registros de autenticación del servidor.

## 3. Fuente de información
Registros Syslog de Linux, especialmente los eventos relacionados
con el servicio SSH (sshd).

## 4. Indicadores que se deben revisar
- Fecha y hora de los intentos.
- Dirección IP de origen.
- Nombre de usuario utilizado.
- Cantidad de intentos fallidos.
- Posible acceso exitoso posterior.

## 5. Herramienta de detección
Consulta KQL preparada para buscar mensajes como
"Failed password" y "authentication failure" en la tabla Syslog.

## 6. Acciones de respuesta propuestas
- Revisar la dirección IP de origen.
- Comprobar si hubo un acceso exitoso.
- Bloquear el origen si se confirma actividad maliciosa,
  siguiendo el procedimiento autorizado.
- Revisar la configuración de SSH.
- Documentar los resultados.

## 7. Estado
Escenario hipotético documentado para fines de aprendizaje.
No corresponde a un incidente detectado en Microsoft Sentinel.
