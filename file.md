# Evaluación — Unidad 2 Tema 2.2
## Búsqueda y recorridos en el BST

| Campo | Dato |
|---|---|
| Nombre | armando |
| Grupo | 2a |
| Materia | Estructura de Datos |
| Fecha | 2026-07-18 |
| Commit | `feat: evaluacion-bst-recorridos-busqueda` |

## Puntaje

| Fase | Puntos obtenidos | Total posible |
|---|---|---|
| Fase 1 — Conceptos de búsqueda | 0 | 8 |
| Fase 2 — Análisis de recorridos | 4 | 6 |
| Fase 3 — Reflexión escrita | 0 | 6 |
| Fase 4 — Codespaces (profesor) | — | 5 |
| **Total (sin Fase 4)** | **4** | **20** |

## Fase 1 — Respuestas

**P1.** ¿Cuántas comparaciones realiza Buscar(60) antes de devolver true?
Respuesta: 1 — lo encuentra directamente sin bajar — Incorrecta

**P2.** ¿Qué devuelve Buscar(35) sobre este árbol?
Respuesta: true — existe entre 30 y 40 — Incorrecta

**P3.** ¿Cuál es el resultado del recorrido InOrder sobre este árbol?
Respuesta: 50 30 20 40 70 60 80 — Incorrecta

**P4.** ¿Qué propiedad del BST garantiza que InOrder produzca orden ascendente?
Respuesta: Que la raíz siempre tiene el valor mayor — Incorrecta

## Fase 2 — Respuestas

**P1.** ¿Cuál es el resultado del recorrido PreOrder sobre el árbol de referencia?
Respuesta: 20 30 40 50 60 70 80 — Incorrecta

**P2.** ¿Cuál es el resultado del recorrido PostOrder sobre el árbol de referencia?
Respuesta: 20 40 30 60 80 70 50 — Correcta

**P3.** Un desarrollador necesita copiar la estructura de un árbol BST para reconstruirlo exactamente igual en otro sistema. ¿Qué recorrido debe usar para serializar los nodos en el orden correcto de inserción?
Respuesta: PreOrder — porque el primer valor siempre es la raíz; insertar en ese orden reconstruye el mismo árbol — Correcta

## Fase 3 — Respuestas abiertas

**Pregunta 1:** Explica con tus propias palabras por qué la búsqueda en un BST es más eficiente que en una lista enlazada. Menciona el costo en términos de comparaciones para ambas estructuras.

wdwdwd

**Pregunta 2:** ¿Cuál es la diferencia entre PreOrder y PostOrder? Describe un caso de uso concreto para cada uno.

dfweff

**Pregunta 3:** Si insertas los valores 10, 20, 30, 40, 50 en ese orden en un BST, ¿qué forma tendrá el árbol resultante? ¿Qué problema representa esto y cómo se resuelve?

efewfeffwf

## Fase 4 — Salida esperada en Codespaces

```
=== Recorridos del árbol BST (50,30,70,20,40,60,80) ===
InOrder:   20 30 40 50 60 70 80
PreOrder:  50 30 20 40 70 60 80
PostOrder: 20 40 30 60 80 70 50

=== Búsqueda ===
Buscar(40): True
Buscar(99): False
Buscar(20): True
```

---
*Generado automáticamente — Evaluación Tema 2.2 — Estructura de Datos*
