# Resolución de referencia

| Alerta | Prioridad de práctica | Decisión y justificación |
|---|---|---|
| AL-101 | Baja | Validar que la hora y el origen concuerdan con el viaje aprobado antes de cerrar. |
| AL-102 | Alta | Escalar la segunda detección en un equipo de finanzas. Registrar qué bloqueó el agente y solicitar evidencia para determinar si hubo ejecución previa. |
| AL-103 | Media | Conservar el mensaje para análisis y comprobar si hay otros destinatarios. La telemetría parcial deja abierta la posibilidad de interacción. |

### Ejemplo de escalación

**AL-102, 09:22 UTC, finance-ws-07.** El agente registró un bloqueo y el contexto indica una detección previa en el mismo equipo. El alcance y la ejecución previa siguen pendientes. Solicitar al equipo de respuesta revisar ambas detecciones, el árbol de procesos y la salud del agente. La prioridad alta corresponde a este ejercicio y se ajustaría al procedimiento del equipo.

Fuente del ejercicio: [eventos sintéticos](../data/events.csv).
