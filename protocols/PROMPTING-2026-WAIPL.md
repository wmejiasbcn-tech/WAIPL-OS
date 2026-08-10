# Prompting 2026 — WAIPL (Outcome-First)

**Fuente canónica:** Documento “Prompting 2026 WAIPL” (resumen oficial WILL-AI Project Lab · agosto 2026)  
**Integrado en:** Super Plantilla Maestra Canónica v3.0 — Capítulo 5  
**Estado:** Aprobado para uso en todos los nodos y agentes del ecosistema

---

## 1. Qué ha cambiado

Los modelos de 2026 razonan, verifican y se auto-corrigen por defecto.  
Instrucciones redundantes de verificación o “piensa profundamente” causan sobreverificación, desperdician tokens y empeoran resultados.

Métricas reportadas (OpenAI / Anthropic 2026):
- +10-15 % en evaluaciones
- –41-66 % tokens
- hasta –67 % coste

## 2. Los 5 anti-hacks (eliminar o transformar HOY)

1. **Eliminar** “verifica tu trabajo” / double-check genérico.  
2. **Eliminar** “piensa profundamente” → usar parámetro `effort` (low / medium / high / xhigh).  
3. **Transformar** SIEMPRE / NUNCA / OBLIGATORIO genéricos → reglas de decisión (“si X, haz Y”).  
4. **Transformar** “sé conciso” universal → criterio preciso de longitud o contenido.  
5. **Eliminar** contradicciones heredadas (una regla, una vez, en un solo sitio).

## 3. Los 4 mandamientos

1. **Esfuerzo (effort)** — controla cuánto piensa el modelo. Empieza bajo.  
2. **Alcance** — frena la expansión no pedida.  
3. **Longitud** — pídela explícita.  
4. **Autonomía** — define hasta dónde llega solo (política de 3 niveles).

## 4. Plantilla canónica Outcome-First (obligatoria)

```
Rol: [Función del modelo en una línea]
Objetivo: [Resultado final requerido]
Criterios de Éxito: [Condiciones medibles de finalización]
Restricciones: [Límites de seguridad, stack técnico y presupuesto]
Formato de Salida: [Estructura, extensión y reglas de formato]
Reglas de Parada: [Condiciones para pedir confirmación o detener]
```

## 5. Política de Autonomía de Tres Niveles (Super Plantilla + Prompting 2026)

- **Nivel 1** (Inspección y Consulta): autonomía total para leer, analizar y generar informes.  
- **Nivel 2** (Ejecución Segura): autonomía para modificar archivos en estado Borrador dentro del Dominio A.  
- **Nivel 3** (Acciones Críticas): obligatoriedad de solicitar confirmación al Soberano o a Carla.

## 6. Uso en WAIPL-Obsidian-Skills

Todo prompt de Agent Skills, NPCs o automatizaciones de este proyecto debe nacer con la plantilla Outcome-First y pasar el filtro de la Super Plantilla v3.0.

---

**Referencia original:** Artículo Alex dc / Mafia IA · 30 jul 2026 · Adaptado e integrado al ADN WAIPL.
