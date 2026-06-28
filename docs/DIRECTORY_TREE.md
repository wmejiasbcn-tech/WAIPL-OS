# DIRECTORY TREE

## Propósito

Este documento constituye el árbol oficial del WAIPL-OS.

Describe la organización física del sistema y sirve como referencia para localizar cualquier componente documental del ecosistema.

---

## Estructura oficial

```text
WAIPL-OS/
│
├── docs/
│   ├── README.md
│   ├── ARCHITECTURE.md
│   ├── DIRECTORY_TREE.md
│   ├── ONTOLOGY.md
│   └── ROADMAP.md
│
├── memory/
│   ├── README.md
│   ├── AGENT.md
│   ├── CHANGELOG.md
│   ├── DECISIONS.md
│   ├── HANDOVER.md
│   ├── LESSONS_LEARNED.md
│   ├── SESSION_LOG.md
│   └── TASKS.md
│
├── projects/
│   ├── README.md
│   ├── active/
│   ├── completed/
│   ├── archive/
│   ├── PROJECT_INDEX.md
│   └── PORTFOLIO.md
│
├── protocols/
│   ├── README.md
│   ├── COMMUNICATION_PROTOCOL.md
│   ├── GOVERNANCE_PROTOCOL.md
│   ├── MEMORY_PROTOCOL.md
│   ├── PROJECT_PROTOCOL.md
│   └── QUALITY_PROTOCOL.md
│
└── templates/
    ├── README.md
    ├── memory/
    ├── projects/
    ├── prompts/
    ├── protocols/
    └── reports/
```

---

## Regla de organización

Toda modificación estructural del WAIPL-OS deberá reflejarse simultáneamente en:

* DIRECTORY_TREE.md
* ARCHITECTURE.md (si afecta a la arquitectura)
* CHANGELOG.md (si supone una evolución del sistema)

---

## Principios

* Una única estructura oficial.
* Organización reproducible.
* Navegación sencilla.
* Escalabilidad controlada.
* Evolución documentada.

---

## Objetivo

Garantizar que cualquier agente humano o IA pueda comprender la estructura completa del WAIPL-OS sin necesidad de inspeccionar manualmente el sistema de archivos.
