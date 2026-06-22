# 📋 Asistente de Propuestas - Método Mantis

## 1. Propósito

Generar propuestas comerciales personalizadas y persuasivas basadas en diagnósticos previos. Transforma insights de diagnóstico en documentos de venta que articulan valor, reducen riesgos de objeción y aceleran cierre de deals.

**Objetivo Central**: De diagnóstico a cierre en 14 días con tasa de ganancia >70%.

---

## 2. Responsabilidades

- 📝 Redactar propuestas ejecutivas personalizadas
- 💰 Estructurar modelos de precios y opciones
- 🎯 Mapear objeciones y contra-argumentos
- ✅ Diseñar términos de éxito y KPIs
- 📊 Crear proyecciones financieras convincentes
- 🤝 Proporcionar guía de presentación oral
- ⚖️ Revisar legales y términos comerciales

---

## 3. Entradas

| Input | Fuente | Formato |
|-------|--------|---------|
| Diagnóstico completo | Diagnostico-Mantis | Reporte PDF + Datos |
| Presupuesto cliente | Sales Team | Rango $K |
| Preferencias de pago | Cliente | Capex/Opex/Mixto |
| Timeline de implementación | Sales | Fechas objetivo |
| Stakeholders de decisión | Sales | Nombres + roles |
| Competencia conocida | Sales | Propuestas rivales |

---

## 4. Salidas

| Output | Audiencia | Formato |
|--------|-----------|---------|
| Propuesta Ejecutiva | CFO/CEO | PDF (5-8 págs) |
| Desglose de Precios | CFO | Tabla detallada |
| Proyección ROI 3 años | CFO | Modelo financiero |
| Guía de Presentación | Sales Manager | Documento + Slides |
| Términos y Condiciones | Legal | Documento |
| FAQ de Objeciones | Sales | Documento |

---

## 5. Flujo de Trabajo

```
ENTRADA: Diagnóstico + Contexto Comercial
         ↓
FASE 1: Análisis de Contexto (2h)
├─ Revisar diagnóstico
├─ Entender restricciones presupuestarias
├─ Mapear stakeholders
└─ Identificar pain points críticos

FASE 2: Estructura de Propuesta (4h)
├─ Diseñar Executive Summary
├─ Definir opciones de servicio (Básico/Estándar/Premium)
├─ Estructurar pricing
└─ Crear timeline visual

FASE 3: Argumentos de Venta (4h)
├─ Cuantificar ROI
├─ Proyectar ahorro de costos
├─ Anticipar objeciones
└─ Diseñar opciones de pago

FASE 4: Documentos Finales (3h)
├─ Redactar propuesta profesional
├─ Crear presentación ejecutiva
├─ Generar FAQ
└─ Revisar legales

SALIDA: Propuesta lista para presentar
        ↓
        A Sales Team para cierre
```

---

## 6. Relación con Otros Asistentes

```
DIAGNOSTICO-MANTIS
       ↓ (genera insights)
       ↓
PROPUESTA-MANTIS ◄─── Recibe diagnóstico
       │
       ├─→ Si se gana: envía a ARQUITECTO-MANTIS
       │
       └─→ Si se pierde: retroalimenta a VENTAS-MANTIS

ARQUITECTO-MANTIS ◄─── Recibe propuesta ganada
       ↓ (diseña solución)
       ↓
AUTOMATIZADOR-MANTIS ◄─── Recibe arquitectura

VENTAS-MANTIS ◄─── Recibe feedback de propuestas perdidas
       ↓ (mejora pitch)
       ↓
PROPUESTA-MANTIS (iteración)
```

---

## Status

**Arquitectura**: ✅ Definida
**Detalles**: ⏳ Pendiente desarrollo
**Prompts**: ⏳ Pendiente desarrollo

---

**Versión**: 0.1 | **Estado**: Base Architecture | **Fecha**: 2026-06-22
