# ONTOLOGY

## Propósito

Este documento define el significado oficial de los conceptos utilizados dentro del WAIPL-OS.

Su objetivo es garantizar que todos los agentes humanos e IA utilicen exactamente el mismo lenguaje institucional.

---

## Principios

- Un concepto tiene una única definición oficial.
- Las definiciones evolucionan, nunca se duplican.
- Todo nuevo concepto deberá incorporarse aquí.
- Ningún documento redefinirá conceptos ya existentes.

---

## Conceptos fundamentales

### WAIPL-OS

Sistema operativo documental e institucional del Will-AI Project Lab.

Constituye la infraestructura de memoria, gobernanza, coordinación y operación compartida del ecosistema.

---

### Agente

Entidad humana o IA capaz de ejecutar trabajo dentro del ecosistema siguiendo los protocolos oficiales.

---

### Memoria institucional

Conocimiento persistente del ecosistema.

No depende de una conversación ni de un agente concreto.

---

### Proyecto

Unidad organizada de trabajo con un objetivo definido, un responsable, un estado y una trazabilidad completa.

---

### Protocolo

Conjunto de reglas que describen cómo debe ejecutarse un determinado proceso dentro del sistema.

---

### Plantilla

Documento reutilizable que normaliza la creación de nuevos contenidos.

---

### Decisión

Resolución adoptada que modifica, condiciona o dirige el funcionamiento del sistema o de un proyecto.

Toda decisión debe registrarse.

---

### Handover

Documento de transferencia entre agentes.

Permite continuar un trabajo sin pérdida de contexto.

---

### Changelog

Historial oficial de evolución del WAIPL-OS.

Registra únicamente cambios estructurales, institucionales o funcionales del sistema.

---

### Session Log

Registro cronológico de cada sesión de trabajo realizada.

---

### Lesson Learned

Aprendizaje institucional obtenido tras una experiencia relevante.

Su objetivo es evitar repetir errores y mejorar continuamente.

---

### Task

Trabajo pendiente de ejecución.

No describe ideas ni decisiones.

---

## Evolución de la ontología

Toda incorporación, modificación o eliminación de conceptos deberá:

- actualizar este documento;
- registrarse en CHANGELOG.md;
- mantenerse compatible con la arquitectura del sistema.

---

## Objetivo

Garantizar que todo el ecosistema WAIPL utilice un lenguaje común, consistente y verificable.

---

### Colaboración institucional

Relación estructurada entre WAIPL y una organización externa, documentada mediante un espacio propio dentro de `collaborations/`, que garantiza la trazabilidad de comunicaciones, documentos, decisiones y resultados.

---

### Espacio de Colaboración Público (ECP)

Espacio documental controlado mediante el cual el WAIPL comparte con una organización externa únicamente la documentación destinada a la colaboración institucional.

Un ECP constituye la interfaz pública entre el WAIPL-OS y una entidad colaboradora, preservando la separación entre la información compartida y la documentación operativa interna del ecosistema.

Características:

- Documentación seleccionada y controlada.
- Trazabilidad completa.
- Transparencia institucional.
- Independencia del sistema operativo interno.
- Reutilizable para cualquier organización colaboradora.

Ejemplos:

- ECP · Sider.ai
- ECP · Google
- ECP · Kaggle
- ECP · gTt-VIH
- ECP · CESIDA
- ECP · Clínic Barcelona

Relación arquitectónica:

WAIPL-OS → Collaborations → Organización → ECP → Documentación pública compartida.
