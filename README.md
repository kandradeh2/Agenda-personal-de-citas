# Resumen del Caso de Uso: Sistema de Reservas de Restaurante

## Descripción del Caso
Sistema de reservas en línea para restaurantes que permite a clientes consultar disponibilidad, realizar reservaciones y gestionar sus reservas de manera eficiente mediante plataforma web y móvil.

## Objetivos
- Permitir búsqueda de disponibilidad por fecha, hora y número de personas
- Facilitar creación, modificación y cancelación de reservas
- Gestionar mesas y horarios disponibles en tiempo real
- Enviar notificaciones automáticas de confirmación

## Requerimientos

### Funcionales (v2)
- RF-01: Búsqueda de disponibilidad con preferencias de ubicación
- RF-02: Realización de reserva con requisitos especiales
- RF-03: Confirmación con código QR
- RF-04: Modificación con notificación al restaurante
- RF-05: Cancelación con ofertas de reprogramación
- RF-06: Sistema de waitlist automatizado
- RF-07: Recordatorios automáticos 24h antes

### No Funcionales (v2)
- RNF-01: Disponibilidad 99.8% del tiempo
- RNF-02: Tiempo de respuesta <2 segundos
- RNF-03: Seguridad GDPR + PCI DSS
- RNF-04: Soporte para 1000 usuarios concurrentes
- RNF-05: Compatibilidad móvil responsive

## Tabla de Pruebas
| ID | Requerimiento | Datos de Entrada | Resultado Esperado |
|----|---------------|------------------|---------------------|
| CPF-01 | RF-01 + RF-02 | fecha, hora, 6 personas, "terraza" | Lista mesas terraza + reserva confirmada |
| CPF-02 | RF-04 + RF-03 | modificar reserva existente | Reserva actualizada + notificación + nuevo QR |
| CPF-03 | RF-05 + RF-06 | cancelar reserva en horario lleno | Mesa liberada + waitlist notificado |

## Mantenimiento Propuesto
**Mantenimiento Perfectivo**: Enfocado en mejorar funcionalidad y experiencia de usuario mediante:
- Sistema de waitlist automatizado
- Recordatorios 24h antes vía SMS/email
- Código QR para check-in rápido
- Preferencias de ubicación
- Optimización de rendimiento

## Reflexión sobre Control de Versiones
El control de versiones es esencial en documentación técnica porque permite gestionar cambios de manera ordenada y recuperar versiones anteriores fácilmente. Facilita la colaboración en equipo sin conflictos y proporciona contexto histórico mediante mensajes de commit, asegurando que la documentación crezca de forma estructurada y mantenible en el tiempo.
