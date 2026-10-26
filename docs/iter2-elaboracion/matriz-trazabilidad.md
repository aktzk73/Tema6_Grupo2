# Matriz de trazabilidad (v1.0-iter2)

| Req | Descripción | CU | Clase | Prueba | ¿Cubierto? |
|---|---|---|---|---|---|
| REQ-001 | Registrar trabajador en el sistema | CU-003 | CLS-Trabajador | PRU-001 | Sí |
| REQ-002 | Registrar entrada y salida | CU-002 | CLS-Marcacion | PRU-002 | Sí |
| REQ-003 | Generar reportes | CU-005, CU-007 | CLS-Reporte, CLS-Asistencia | PRU-003 | Sí |
| REQ-004 | Autenticar administrador | CU-001 | CLS-Administrador | PRU-004 | Sí |
| REQ-005 | Configurar turnos y tolerancia | CU-004 | CLS-Turno | PRU-005 | Sí |
| REQ-006 | Corregir asistencia con motivo | CU-006 | CLS-Asistencia | PRU-006 | Sí |
| REQ-007 | Cambiar contraseña del administrador | CU-008 | CLS-Administrador | PRU-007 | Sí |
| REQ-008 | Calcular faltas y horas extras | CU-009 | CLS-Asistencia, CLS-Turno | PRU-008 | Sí |

**Cobertura:** 8 de 8 requisitos con prueba = 100 %

Fórmula: (requisitos con prueba ÷ requisitos totales) × 100.
