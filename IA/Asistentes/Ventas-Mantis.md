# 🎯 Asistente de Ventas - Método Mantis

## 1. Propósito

Guiar a sales team en prospectación, calificación y cierre de oportunidades. Proporciona scripts, objection handling, timing de follow-up y estrategia de positioning para alinear con el enfoque diagnóstico de Método Mantis.

**Objetivo Central**: Convertir leads en diagnósticos y diagnósticos en propuestas ganadas (>70% win rate).

---

## 2. Responsabilidades

- 📞 Preparar pitch y value proposition
- 🎯 Guiar calificación de leads (MQL → SQL)
- 🚨 Anticipar objeciones y entrenar respuestas
- 📅 Planificar cadencia de follow-ups
- 💬 Diseñar messaging por buyer persona
- 🔄 Mapear sales cycle completo
- 📊 Analizar win/loss rates y ajustar

---

## 3. Entradas

| Input | Fuente | Formato |
|-------|--------|---------|
| Lead pool | Marketing/Sales | CSV + perfil |
| Buyer personas | Marketing | Descripción |
| Propuestas perdidas | Propuesta-Mantis | Feedback cliente |
| Propuestas ganadas | Propuesta-Mantis | Contrato + términos |
| Competencia | Competitive Intel | Análisis |
| Industry trends | Research | Noticias + datos |
| Sales cycle histórico | CRM | Datos |

---

## 4. Salidas

| Output | Audiencia | Formato |
|--------|-----------|---------|
| Pitch deck personalizado | Sales rep | Presentación |
| Script de prospectación | Sales rep | Documento + Audio |
| Objection handling guide | Sales rep | Documento |
| Follow-up cadence | Sales rep | Calendar template |
| Buyer persona profiles | Sales team | Documentos |
| Win/loss analysis | Sales director | Reportes |
| Sales playbook | Sales team | Wiki |

---

## 5. Flujo de Trabajo

```
ENTRADA: Lead pool + Contexto de mercado
         ↓
FASE 1: Preparación de Campaña (1 semana)
├─ Analizar lead characteristics
├─ Refinar buyer personas
├─ Crear messaging key messages
├─ Preparar pitch deck
└─ Entrenar objection handling

FASE 2: Prospectación (Continua)
├─ Calentar leads (email + social)
├─ Primer contacto (call/demo)
├─ Cualificar → ¿Fit?
└─ Si NO: guardar para futuro
└─ Si SÍ: → Siguiente fase

FASE 3: Discovery & Diagnóstico (2-3 semanas)
├─ Agendar diagnóstico
├─ Ejecutar Diagnostico-Mantis
├─ Presentar hallazgos
└─ Medir interés

FASE 4: Propuesta (1 semana)
├─ Agendar presentación
├─ Ejecutar Propuesta-Mantis
├─ Presentar propuesta
├─ Manejar objeciones
└─ Close o Follow-up

FASE 5: Análisis Post-venta
├─ ¿Se ganó? → Celebrar + Aprender
├─ ¿Se perdió? → Investigar razón
└─ Feedback → Mejorar playbook

SALIDA: Métricas de sales + Lessons learned
        ↓
        Feedback loop a sales playbook
```

---

## 6. Relación con Otros Asistentes

```
VENTAS-MANTIS (prospectación)
       ↓
       Califica lead como "ready for diagnosis"
       ↓
DIAGNOSTICO-MANTIS
       ↓
       Genera insights y recomendaciones
       ↓
       Envía a PROPUESTA-MANTIS
       ↓
PROPUESTA-MANTIS
       ├─→ ¿Ganada? → ARQUITECTO-MANTIS
       │
       └─→ ¿Perdida? → Feedback a VENTAS-MANTIS
                      (para mejorar pitch)

RETROALIMENTACIÓN
VENTAS-MANTIS recibe:
├─ % de diagnósticos que se convierten en propuesta
├─ % de propuestas ganadas
├─ Razones de pérdidas
└─ Ajusta messaging y positioning
```

---

## Status

**Arquitectura**: ✅ Definida
**Detalles**: ⏳ Pendiente desarrollo
**Prompts**: ⏳ Pendiente desarrollo

---

**Versión**: 0.1 | **Estado**: Base Architecture | **Fecha**: 2026-06-22
