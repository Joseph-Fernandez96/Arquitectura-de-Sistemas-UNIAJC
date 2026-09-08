# Requerimientos no funcionales
| # |   Atributo  |     Metrica             |     Umbral       |     Condicion de carga    |   Verificacion  |  Consecuencia si no se cumple  |
|---|-------------|-------------------------|------------------|---------------------------|-----------------|--------------------------------|
| 1 | Rendimiento |    p95 de latencia      |  menor a 400 ms  | 200 usuarios concurrentes | Prueba de carga | El usuario abandona la reserva |
| 2 | Costo |Gasto mensual recurrente acumulado en infraestructura de nube.|<= 50$ USD/mes en costos fijos de servidor y bases de datos.|Volumen operativo normal de 50 pedidos al dia.|Alertas presupuestarias automatizadas en el proveedor cloud|Escalar hacia abajo los recursos asignados.|
| 3 | Seguridad   | Cifrado de datos en transito y reposo | 100% de los datos cifrados (TLS 1.3 / AES-256) | Operacion normal y picos de trafico | Auditoria de configuracion y escaneo de vulnerabilidades | Exposicion de datos sensibles y penalizaciones legales/regulatorias |
|---|---|---|---|---|---|---|---|---|---|---|---|---|

## Escenarios completos### 
Escenario 1
-Fuente:
-Estimulo:
-Artefacto:
-Entorno:
-Respuesta:
-Medida: