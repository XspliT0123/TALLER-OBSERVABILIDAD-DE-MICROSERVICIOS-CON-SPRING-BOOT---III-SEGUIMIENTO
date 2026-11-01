# Taller de observabilidad: Spring Boot Actuator + Micrometer

Proyectos: `microservicio-productos` (8081) y `microservicio-pedidos` (8082).

## Ejecución
1. Abrir cada carpeta como proyecto Maven en IntelliJ (JDK 21) y esperar la sincronización.
2. Ejecutar primero `MicroservicioProductosApplication`, luego `MicroservicioPedidosApplication`.
3. Probar `http://localhost:8082/pedidos/1`.
4. El archivo `microservicio-pedidos/pruebas-observabilidad.http` trae todas las peticiones del taller.

Por línea de comandos (con Maven instalado): `mvn spring-boot:run` dentro de cada carpeta.
