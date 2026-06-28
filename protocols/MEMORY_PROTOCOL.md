# MEMORY PROTOCOL

## Propósito

Este protocolo define cómo funciona la memoria persistente institucional del WAIPL-OS.

Su objetivo es garantizar continuidad entre sesiones, trazabilidad completa, conservación del conocimiento y coordinación entre agentes humanos e IA.

---

## Objetivos

- Evitar pérdida de contexto.
- Evitar trabajo duplicado.
- Permitir relevos entre agentes.
- Mantener trazabilidad completa.
- Convertir la experiencia en conocimiento institucional.

---

## Componentes

La memoria está formada por:

- AGENT.md
- DECISIONS.md
- HANDOVER.md
- TASKS.md
- SESSION_LOG.md
- LESSONS_LEARNED.md
- CHANGELOG.md

Cada documento tiene una única responsabilidad.

Ningún documento debe duplicar la función de otro.

---

## Flujo obligatorio

Antes de comenzar cualquier trabajo:

1. Leer AGENT.md.
2. Revisar DECISIONS.md.
3. Consultar TASKS.md.
4. Leer el último SESSION_LOG.md.
5. Revisar HANDOVER.md si existe un relevo.
6. Comenzar únicamente cuando exista contexto suficiente.

Al finalizar cualquier trabajo:

1. Actualizar TASKS.md.
2. Registrar decisiones en DECISIONS.md.
3. Registrar la sesión en SESSION_LOG.md.
4. Actualizar HANDOVER.md si otro agente continuará.
5. Registrar aprendizajes en LESSONS_LEARNED.md cuando corresponda.
6. Registrar cambios estructurales en CHANGELOG.md cuando proceda.

---

## Principios

- Una única fuente de verdad.
- Información verificable.
- Trazabilidad completa.
- Evolución documentada.
- Aprendizaje institucional continuo.
- Gobernanza compartida.
