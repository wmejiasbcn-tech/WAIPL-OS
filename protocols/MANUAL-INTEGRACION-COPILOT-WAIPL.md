# MANUAL DE PROCEDIMIENTOS DE INTEGRACIÓN CON GITHUB COPILOT  
**WAIPL · Super Plantilla Maestra Canónica v3.0**

**Versión:** 1.0  
**Fecha:** 2026-08-10  
**Estado:** Borrador canónico (pendiente de Acta de Nacimiento)  
**Nodo redactor:** Aether-Hermes  
**Alcance:** Integración actual y futura de GitHub Copilot (y agentes derivados) con el ecosistema WAIPL y el proyecto WAIPL-Obsidian-Skills.

---

## 1. Propósito

Definir el procedimiento seguro, trazable y simbiótico para que GitHub Copilot (y futuras capacidades agenticas de Microsoft/GitHub) opere dentro de los límites del ADN WAIPL:

- Honestidad Absoluta
- Precisión Shinkansen
- Apertura Radical
- Soberanía Mínima
- Flujo Ininterrumpido (planes A/B/C)
- Compartimentación Dominio A / Dominio B
- Autonomía de tres niveles + Human-in-the-Loop

## 2. Integraciones actuales (2026)

| Capacidad | Uso permitido | Nivel de autonomía | Notas |
|-----------|---------------|--------------------|-------|
| Completions en código | Dominio A, archivos en estado Borrador | Nivel 2 | Solo stack activo del laboratorio |
| Chat de Copilot | Consulta y generación de informes | Nivel 1 | Debe usar plantilla Outcome-First |
| Copilot Workspace / Agent | Propuestas de cambios | Nivel 2 → 3 si toca producción o estados Aprobado | Requiere breakpoint simbiótico |
| Sugerencias en Markdown / vault | Solo carpetas Dominio A | Nivel 2 | Nunca en 03-PERSONAL |

## 3. Integraciones futuras (hipótesis controladas)

- Agentes multi-archivo con memoria persistente del vault
- Integración nativa con health-check ICP
- Ejecución de skills Osmani desde Copilot
- Circuit-breakers automáticos ligados a tickets DESV

Toda nueva capacidad debe pasar por:
1. Evaluación de impacto (NPC-ANA + NPC-MEJ)
2. Definición de breakpoints
3. Actualización de este manual
4. Validación del Soberano o Carla (Nivel 3)

## 4. Procedimiento de integración (paso a paso)

1. **Percepción**  
   - Registrar la intención de uso con UUID v4 + timestamp ISO 8601 + hash del contexto.

2. **Cognición**  
   - Verificar que el alcance está en Dominio A.  
   - Calcular nivel de certeza. Si < 95 % → `trigger_symbiotic_pause()`.

3. **Acción**  
   - Aplicar plantilla Outcome-First.  
   - Ejecutar solo hasta el nivel de autonomía autorizado.  
   - Generar log append-only en 08-AUDITORIA.

4. **Cierre**  
   - Actualizar estado del conocimiento.  
   - Si hubo desviación → ticket DESV-YYYYMMDD-NNN.

## 5. Runbooks de contingencia específicos (C-Copilot)

Basados en C-01 a C-08 de la Super Plantilla:

- **C-C01** Pérdida de contexto / memoria de Copilot → Aislar sesión, reintentar con prompt mínimo, escalar a Nivel 3.
- **C-C02** Rate limit o cuota excedida → Backoff exponencial + cola de retención en 01-INBOX.
- **C-C03** Alucinación o código no trazable → Marcar como Bloqueado, generar ticket DESV, no mergear.
- **C-C04** Desviación de nomenclatura o estructura canónica → Rechazar cambio, regenerar bajo plantilla.
- **C-C05** Fallo en cascada (múltiples archivos) → Circuit breaker, congelar PR, notificar a Carla/Soberano.
- **C-C06** Compromiso de integridad (hash SHA-256) → Cuarentena inmediata.
- **C-C07** Sobrecarga del Soberano (>10 escalados/día) → Activar modo conservador (solo Nivel 1).
- **C-C08** Drift de comportamiento de Copilot → Recalibración mensual obligatoria + revisión de system prompts.

## 6. Reglas inviolables

- Ningún agente (incluido Copilot) tiene acceso predeterminado al Dominio B (03-PERSONAL).
- Todo cambio en estado Aprobado o en producción exige confirmación humana (Nivel 3).
- Todo prompt debe ser Outcome-First.
- Todo artefacto generado debe llevar nomenclatura canónica y estado de control.

## 7. Cadena de auditoría

Copilot → NPC-AUD → tickets DESV → 08-AUDITORIA → Dashboard ICP → Soberano / Carla.

## 8. Próximos pasos recomendados

1. Validar este manual con el Soberano.
2. Probar breakpoints con un caso real de WAIPL-Obsidian-Skills.
3. Actualizar Dashboard ICP para incluir métrica de uso de Copilot.
4. Incluir este manual en el Acta de Nacimiento del proyecto.

---

**Declaración**  
Este manual nace y se mantiene bajo el filtro de la Super Plantilla Maestra Canónica v3.0.  
Cualquier modificación futura requiere el mismo rigor.
