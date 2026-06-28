# CHANGELOG

## Propósito

Este documento constituye el historial oficial de evolución del WAIPL-OS.

Registra únicamente cambios estructurales, funcionales o institucionales del sistema.

No registra sesiones de trabajo, decisiones individuales ni tareas operativas.

---

## Qué debe registrarse

- Fecha
- Versión
- Cambio realizado
- Motivo
- Impacto
- Responsable (agente o persona)

---

## Reglas

- Nunca modificar registros anteriores.
- Cada cambio genera una nueva entrada.
- Mantener siempre el orden cronológico.
- Describir únicamente cambios ya implementados.

---

## Historial de evolución

### 2026-06-28 · Versión 1.1

**Cambio realizado:**

- Incorporación del espacio institucional de Sider.ai y su documentación inicial.

**Motivo:**

Separar las relaciones institucionales de los proyectos operativos y proporcionar un espacio permanente para documentar la interacción con organizaciones externas.

**Implementación:**

- Creación del módulo `collaborations/`.
- Creación del espacio institucional `collaborations/sider-ai/`.
- Incorporación de la documentación institucional de Sider.ai.
- Actualización de `ARCHITECTURE.md`.
- Actualización de `DIRECTORY_TREE.md`.
- Actualización de `ONTOLOGY.md`.

**Impacto:**

El WAIPL-OS pasa a diferenciar explícitamente:

- Módulos documentales (`docs/`)
- Memoria institucional (`memory/`)
- Proyectos (`projects/`)
- Protocolos (`protocols/`)
- Plantillas (`templates/`)
- Colaboraciones institucionales (`collaborations/`)

Con ello se consolida la evolución del WAIPL-OS hacia un sistema operativo de ingeniería del conocimiento basado en módulos especializados.
