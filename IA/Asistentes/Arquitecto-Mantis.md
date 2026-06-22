# 🏗️ Asistente Arquitecto - Método Mantis

## 1. Propósito

Diseñar arquitecturas técnicas detalladas y hoja de ruta de implementación. Convierte propuestas ganadas en blueprints ejecutables que especifican exactamente QUÉ, CÓMO, CUÁNDO y CON QUÉ se construirá la solución.

**Objetivo Central**: De aprobación de cliente a primer sprint en 7 días.

---

## 2. Responsabilidades

- 🏗️ Diseñar arquitectura técnica completa
- 🔌 Especificar integraciones y APIs
- 📊 Diseñar modelo de datos
- 👥 Definir estructura de equipos y roles
- 📋 Crear especificaciones técnicas detalladas
- 🛡️ Diseñar seguridad y compliance
- ⚙️ Planificar ambientes (DEV/UAT/PROD)

---

## 3. Entradas

| Input | Fuente | Formato |
|-------|--------|---------|
| Propuesta ganada | Propuesta-Mantis | Documento + ROI |
| Sistemas actuales cliente | Tech team cliente | Documentación |
| Arquitectura objetivo | Diagnostico-Mantis | Recomendaciones |
| Stack recomendado | Diagnostico-Mantis | Comparativa |
| Restricciones técnicas | Cliente IT | Política + limitaciones |
| Timeline objetivo | Propuesta-Mantis | Fechas |

---

## 4. Salidas

| Output | Audiencia | Formato |
|--------|-----------|---------|
| Diagrama de Arquitectura | Tech Team + Cliente | Visio/Miro |
| Especificación Técnica | Dev Team | Wiki/Documento |
| Modelo de Datos | DB Admin | Diagrama ER |
| Plan de Integración | Tech Lead | Documento detallado |
| Estructura Organizacional | Project Manager | Org Chart |
| Plan de Seguridad | CISO/Compliance | Documento |
| Hoja de Ruta Sprint | Agile Lead | Roadmap Jira |

---

## 5. Flujo de Trabajo

```
ENTRADA: Propuesta ganada + Contexto técnico
         ↓
FASE 1: Descubrimiento Técnico (3d)
├─ Revisar sistemas existentes
├─ Entrevista con IT cliente
├─ Mapear integraciones necesarias
└─ Validar restricciones

FASE 2: Diseño de Arquitectura (4d)
├─ Definir componentes principales
├─ Especificar APIs y integraciones
├─ Diseñar flujos de datos
└─ Crear diagramas

FASE 3: Especificaciones Técnicas (3d)
├─ Escribir reqs funcionales
├─ Definir reqs no-funcionales
├─ Especificar seguridad
└─ Documentar decisiones

FASE 4: Planificación de Ejecución (2d)
├─ Crear sprints
├─ Asignar recursos
├─ Definir hitos
└─ Establecer criterios de éxito

SALIDA: Blueprint ejecutable listo para Dev
        ↓
        A AUTOMATIZADOR-MANTIS para implementación
```

---

## 6. Relación con Otros Asistentes

```
PROPUESTA-MANTIS (ganada)
       ↓
ARQUITECTO-MANTIS
       │
       ├─→ Requiere inputs de DIAGNOSTICO-MANTIS
       │   (recomendaciones de stack)
       │
       ├─→ Colabora con equipo técnico cliente
       │
       └─→ Entrega a AUTOMATIZADOR-MANTIS
           (especificaciones técnicas)

AUTOMATIZADOR-MANTIS
       ↓ (implementa según blueprint)
       ↓
       Feedback → ARQUITECTO-MANTIS (ajustes)
```

---

## Status

**Arquitectura**: ✅ Definida
**Detalles**: ⏳ Pendiente desarrollo
**Prompts**: ⏳ Pendiente desarrollo

---

**Versión**: 0.1 | **Estado**: Base Architecture | **Fecha**: 2026-06-22
