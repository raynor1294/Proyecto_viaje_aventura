# Proyecto_viaje_aventura

 Sistema de Gestión - Viaje Aventura

##  Planteamiento del Caso

La agencia de turismo **Viaje Aventura**, especializada en expediciones, trekking y deportes extremos, enfrenta actualmente dificultades operativas debido a que gestiona sus reservas, disponibilidad de rutas y asignación de guías de forma manual mediante hojas de cálculo dispersas. Este proceso genera duplicidad de reservas, desactualización en los cupos disponibles y demoras en la confirmación hacia los clientes.

Para resolver esta problemática, se propone el desarrollo de una solución de software centralizada que permita automatizar y optimizar el flujo de operaciones de la agencia. El sistema permitirá a los clientes explorar el catálogo de expediciones (filtrando por nivel de dificultad, destino y fechas), verificar disponibilidad en tiempo real y realizar reservas de manera segura. Por su parte, el personal administrativo y los guías podrán gestionar las rutas, controlar los cupos máximos por grupo y monitorear el estado de cada excursión.

### Objetivos del Sistema
* **Seguridad y Control de Acceso:** Implementar autenticación robusta mediante encriptación de contraseñas (`bcrypt`) para proteger los datos de clientes, guías y administradores.
* **Gestión de Catálogo y Reservas:** Centralizar la administración de paquetes turísticos, controlando automáticamente el stock de cupos y evitando el sobreagendamiento.
* **Integración de Servicios Externos:** Consumir APIs externas (mediante `requests`) para obtener información actualizada relevante para las expediciones, como pronósticos meteorológicos o conversión de divisas.
* **Trazabilidad:** Mantener un historial claro de reservas, pagos y asignaciones de guías por cada ruta programada.

### Actores Principales
* **Cliente / Turista:** Usuario que consulta expediciones, crea su cuenta, realiza reservas y revisa su historial de viajes.
* **Administrador:** Encargado de crear y actualizar paquetes turísticos, definir precios, establecer cupos y gestionar usuarios.
* **Guía de Aventura:** Usuario asignado a las expediciones que consulta su itinerario y la lista de participantes confirmados.
