# Tablero de Riesgo Operativo — SURA

Prototipo de la salida (Bloque 3) del sistema multi-agente de gestión del riesgo
operativo. Tablero orientado a eventos, con dos vistas: líderes de proceso y equipo
de riesgos.

## Ver el tablero

Una vez activado GitHub Pages, el tablero queda disponible en el link del repositorio
(ver sección Settings → Pages).

## Qué contiene

- **Tira de eventos**: los disparadores que ejecutaron el modelo.
- **Vista líderes**: conclusión del agente, reporte del evento (diagnóstico y
  predicción), alertas, sugerencias accionables y conexión con la estrategia.
- **Vista equipo de riesgos**: score de procesos (por riesgo real y por calidad de
  información), mapa de calor, interconexión entre procesos, conexión con el modelo
  operativo, conexión estrategia–realidad–procesos, tabla de riesgos con detalle e
  indicadores.

## Notas

- Es un único archivo `index.html` sin dependencias externas.
- Los datos y eventos son de ejemplo, ilustrativos; no corresponden a una evaluación
  real.
- Para versiones con datos reales, debe alojarse en infraestructura interna con
  control de acceso.
