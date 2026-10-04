# CANAL LOG
## Plantilla pública de memoria cronológica · CAP v0.3

Este archivo es opcional y pertenece a cada instancia del CAP.

Una distribución pública debe entregarlo limpio. La memoria de un operador no se hereda a otro.

## Reglas

- Registrar al final de una sesión, no por obligación durante el trabajo.
- Una entrada breve es suficiente.
- No registrar datos personales o sensibles si no son necesarios para el propósito de la instancia.
- No reescribir entradas antiguas para hacerlas encajar con una lectura posterior.
- Si aparece un matiz o corrección, añadir una nueva entrada.
- Si registrar aumenta la carga sin aportar continuidad, no registrar.

## Formato sugerido

```text
AAAA-MM-DD
[TEMA]

Contexto:
Núcleo:
Decisión u observación:
Estado:
IA:
Tipo: Registro / Lectura / Mixto
```

## Ejemplo ficticio

```text
2026-10-04
[REVISIÓN DE UNA DECISIÓN]

Contexto: comparación de dos alternativas con documentación pública.
Núcleo: separar hechos comprobados de inferencias antes de decidir.
Decisión u observación: pedir fuente primaria para el punto material pendiente.
Estado: 2
IA: modelo conversacional
Tipo: Mixto
```

El silencio también es una salida válida. El log debe servir al método, no convertirse en una carga.
