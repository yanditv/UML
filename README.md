# Diagrama de clases

## Ejercicio

Diseñar un sistema de reservación de habitaciones para un hotel que permita manejar información sobre habitaciones, huespedes, reservaciones y pagos.

### Requisitos

- Cada habitación tiene un número, un tipo(simple, doble, suite), un precio y un estado(disponible, reservada)
- Un huésped tiene un nombre, una identificación única, y un historial de reservaciones.
- Una reservación incluye información sobre la habitación reservada, el huesped, las fechas de entrada y sálida, el costo total.
- Los pagos están asociados a una reservación e incluyen un monto y una fecha de pago.
- El sistema debe permitir:
  - Registrar nuevas habitaciones y huespedes
  - Registrar y cancelar reservaciones
  - Registrar pagos

# Diagrama de casos de uso

## Ejercicio: Sistema de Reservación de Hotel

### Contexto:

Eres parte del equipo que diseña un sistema para la gestión de reservas de un hotel. El sistema debe permitir a los clientes buscar habitaciones, hacer reservas y pagar en línea. Los empleados del hotel deben gestionar las reservas, registrar clientes en el sistema y actualizar la disponibilidad de las habitaciones. El gerente del hotel necesita acceder a reportes sobre las ocupaciones y ganancias.

### Requerimientos del sistema:

Los clientes deben:

- Buscar habitaciones disponibles según las fechas y el tipo de habitación.
- Realizar una reserva de habitación.
- Pagar la reserva en línea.

Los empleados deben:

- Consultar y gestionar las reservas realizadas por los clientes.
- Registrar a los clientes cuando lleguen al hotel.
- Actualizar la disponibilidad de las habitaciones (por ejemplo, cuando se realiza el check-out).
  El gerente debe:

- Generar reportes sobre las ocupaciones (habitaciones ocupadas, disponibles, etc.).
- Generar reportes financieros (ingresos generados por las reservas).
- El sistema debe enviar notificaciones automáticas:
  - Al cliente, cuando su reserva se confirma.
  - Al cliente, cuando se acerca la fecha de su check-in.

### Tareas para el diagrama:

- Identificar los actores: Enumera quiénes interactuarán con el sistema. (Por ejemplo: Cliente, Empleado, Gerente, Sistema de Notificaciones).

- Definir los casos de uso: Para cada actor, identifica las acciones principales que puede realizar en el sistema (por ejemplo, "Buscar habitación", "Realizar pago").

- Relacionar actores con casos de uso: Usa líneas para conectar cada actor con los casos de uso que le correspondan.

- Añadir relaciones entre casos de uso:
  - Usa inclusión (<<include>>) si un caso de uso es parte de otro.
  - Usa extensión (<<extend>>) si un caso de uso amplía otro bajo ciertas condiciones.
