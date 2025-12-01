# Requerimientos del Sistema de Gestión CAT

## Requerimientos Funcionales
Estos describen las funcionalidades principales que el sistema debe proporcionar.

1. El sistema debe permitir a los usuarios registrar solicitudes de soporte con detalles como descripción, tipo de problema, prioridad y adjuntos (archivos).
2. Los administradores deben poder asignar solicitudes a técnicos específicos y actualizar el estado (pendiente, en progreso, resuelto).
3. Los usuarios deben consultar el estado y el historial de sus propias solicitudes a través de un dashboard personal.
4. El sistema debe generar reportes automáticos (mensuales) con métricas como número de tickets resueltos, tiempo promedio de resolución y distribución por prioridad.
5. Debe enviar notificaciones por email o in-app a los usuarios y técnicos al cambiar el estado de una solicitud.

## Requerimientos No Funcionales
Estos describen atributos de calidad como rendimiento, seguridad y usabilidad.

1. El sistema debe ser responsive y accesible desde dispositivos móviles (compatible con browsers modernos como Chrome, Firefox en iOS/Android).
2. Debe soportar al menos 100 usuarios concurrentes sin degradación significativa de rendimiento (tiempo de respuesta < 2 segundos).
3. La autenticación debe ser segura, utilizando HTTPS, encriptación de datos sensibles y integración con cuentas universitarias (ej: OAuth o LDAP).
4. El sistema debe cumplir con estándares de accesibilidad (WCAG 2.1) para usuarios con discapacidades, incluyendo soporte para lectores de pantalla.
5. Debe tener alta disponibilidad (uptime > 99%), con backups automáticos y recuperación de datos en caso de fallos.
