====================================================================
EJERCICIO 1 DE CARGA EN JMETER - SERVICIOS DE LOGIN
====================================================================

Este repositorio contiene el script de automatización de pruebas de
carga del servicio de Login utilizando JMeter.

--------------------------------------------------------------------
1. RESUMEN DE RESULTADOS
--------------------------------------------------------------------
- Usuarios Concurrentes: 15
- Rendimiento Promedio Alcanzado: 39.4 TPS (Meta original: 20 TPS)
- Tiempo de Respuesta Promedio: 377 ms
- Tasa de Error Final: 0.57% (Umbral máximo de aceptación solicitado: 3.00%)
- Muestras Totales Procesadas: 41,719
- Duración del Test Sostenido: 17 minutos y 39 segundos

--------------------------------------------------------------------
2. INSTRUCCIONES PARA LA EJECUCIÓN DEL SCRIPT
--------------------------------------------------------------------
Script 'Servicios Login Ejercicio1.jmx':

1. Abrir el archivo '.jmx' en Apache JMeter.
2. Seleccionar el componente 'Summary Report' o 'View Results Tree'.
3. Presione el botón 'Start (Play)'.
4. El script se ejecutará en bucle de forma INFINITA para mantener
   la concurrencia activa de los 15 usuarios, estabilizar las
   métricas de rendimiento y asegurar la inyección continua de carga.
5. NOTA: Para concluir la prueba de forma controlada
   y revisar las métricas finales, presione manualmente el botón
   'Stop (Signo de Pare)' ubicado en la barra de herramientas superior una
   vez recopiladas las muestras deseadas.

====================================================================