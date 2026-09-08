# Requerimientos no funcionales
| # |   Atributo  |     Metrica             |     Umbral       |     Condicion de carga    |   Verificacion  |  Consecuencia si no se cumple  |
|---|-------------|-------------------------|------------------|---------------------------|-----------------|--------------------------------|
| 1 | Rendimiento |    p95 de latencia      |  menor a 400 ms  | 200 usuarios concurrentes | Prueba de carga | El usuario abandona la reserva |
|---|-------------|-------------------------|------------------|---------------------------|-----------------|--------------------------------|
|   |             |Gasto mensual recurrente | <= 50$ USD/mes en|Volumen operativo normal de|Alertas presupue-|Escalar hacia abajo los recursos|
| 2 | Costo       |acumulado en             | costos fijos de  |50 pedidos al dia.         |starias automati-|asignados.                      |
|   |             |infraestructura de       | servidor y base  |                           |zadas en el prov-|                                |
|   |             |nube.                    | datos.           |                           |eedor cloud.     |                                |
|---|-------------|-------------------------|------------------|---------------------------|-----------------|--------------------------------|
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