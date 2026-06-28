# ARCHITECTURE

## Propósito

Este documento define la arquitectura conceptual del WAIPL-OS.

Describe cómo se organizan sus componentes, cuáles son sus responsabilidades y cómo interactúan entre sí para formar un único sistema operativo documental.

---

## Principios arquitectónicos

* Una única fuente de verdad.
* Separación clara de responsabilidades.
* Bajo acoplamiento entre componentes.
* Alta cohesión interna.
* Trazabilidad completa.
* Evolución controlada.
* Escalabilidad institucional.

---

## Componentes principales

### docs/

Define el conocimiento estructural del sistema.

Responde a la pregunta:

> ¿Cómo está construido WAIPL-OS?

---

### memory/

Conserva la memoria institucional permanente.

Responde a la pregunta:

> ¿Qué sabe el sistema y cómo ha evolucionado?

---

### projects/

Gestiona el trabajo operativo del ecosistema.

Responde a la pregunta:

> ¿Qué estamos construyendo?

---

### protocols/

Define las normas oficiales del sistema.

Responde a la pregunta:

> ¿Cómo debemos trabajar?

---

### templates/

Garantiza la consistencia documental.

Responde a la pregunta:

> ¿Cómo debe escribirse la información?

---

## Relaciones

```text
docs
 │
 ├── define la arquitectura
 │
 ├──────────────┐
 │              │
 ▼              ▼
protocols     templates
 │              │
 └──────┬───────┘
        ▼
     projects
        │
        ▼
      memory
        │
        ▼
     CHANGES
        │
        ▼
      docs
```

El sistema forma un ciclo continuo de evolución documentada.

---

## Regla fundamental

Ningún componente del WAIPL-OS deberá duplicar la responsabilidad de otro componente.

Cada documento tiene un único propósito y constituye la fuente oficial de información de su ámbito.

---

## Resultado esperado

Una arquitectura capaz de ser comprendida, utilizada y ampliada por cualquier agente humano o IA sin depender del conocimiento implícito de sus autores.

---

### collaborations/

Gestiona las relaciones institucionales del ecosistema WAIPL.

Contiene la documentación, el seguimiento, las decisiones, las comunicaciones y los entregables asociados a cada organización con la que el ecosistema interactúa.
