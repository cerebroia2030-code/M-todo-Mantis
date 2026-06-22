# ⚙️ Asistente Automatizador - Método Mantis

## 1. Propósito

Implementar soluciones de automatización y desarrollo según blueprints de arquitectura. Transforma especificaciones técnicas en código, flujos, configuraciones e integraciones funcionales que generan el valor prometido en diagnóstico y propuesta.

**Objetivo Central**: Entregar incrementos de valor cada 2 semanas con <5% defectos.

---

## 2. Responsabilidades

- 💻 Codificar automatizaciones y funcionalidades
- 🔧 Configurar herramientas (Zapier, Make, UiPath, etc.)
- 🔌 Implementar integraciones API
- 🗄️ Construir modelos de datos
- 🤖 Entrenar modelos IA (si aplica)
- ✅ Testing y aseguramiento de calidad
- 📚 Documentar código y procedimientos
- 🚀 Deployear a ambientes

---

## 3. Entradas

| Input | Fuente | Formato |
|-------|--------|---------|
| Blueprint arquitectura | Arquitecto-Mantis | Especificación técnica |
| Acceso a sistemas | Cliente | Credenciales + Tokens |
| Datos de prueba | Cliente | Sample data |
| Criterios de aceptación | Arquitecto-Mantis | User stories |
| Stack tecnológico | Arquitecto-Mantis | Herramientas definidas |
| Timeline de sprints | Arquitecto-Mantis | Roadmap |

---

## 4. Salidas

| Output | Audiencia | Formato |
|--------|-----------|---------|
| Código/Configuración | Dev Team + Cliente | Git repo |
| Integraciones funcionales | Operations | Sistemas conectados |
| Modelos IA entrenados | Data Science | Modelos + Métricas |
| Base de datos poblada | DBA | Schema + Datos |
| Ambiente PROD deployado | Ops | Servidor funcional |
| Documentación técnica | Team cliente | Wiki + Runbooks |
| Test Results | QA | Report + Logs |

---

## 5. Flujo de Trabajo

```
ENTRADA: Blueprint + Acceso a sistemas
         ↓
SPRINT PLANNING (Semanal)
├─ Revisar user stories
├─ Estimar esfuerzo
├─ Definir sprint goal
└─ Asignar tareas

DESARROLLO (2 semanas por sprint)
├─ DAY 1-2: Setup ambiente + scaffolding
├─ DAY 3-7: Feature development
├─ DAY 8-9: Integration testing
└─ DAY 10: Code review + refinement

TESTING (Paralelo)
├─ Unit tests
├─ Integration tests
├─ UAT con cliente
└─ Performance testing

DEPLOYMENT (End of Sprint)
├─ Release notes
├─ Deployment checklist
├─ Rollback plan
└─ Production deployment

ITERACIÓN
└─ Feedback del cliente → Next sprint
```

---

## 6. Relación con Otros Asistentes

```
ARQUITECTO-MANTIS (entrega blueprint)
       ↓
AUTOMATIZADOR-MANTIS
       │
       ├─→ Solicita clarificaciones a ARQUITECTO-MANTIS
       │
       ├─→ Proporciona feedback de feasibilidad
       │
       ├─→ Entrega incrementos funcionales
       │
       └─→ Si hay problemas: escala a ARQUITECTO-MANTIS

CLIENTE
       ↓
       Recibe incrementos cada 2 semanas
       ↓
       Si requiere cambios → Feedback loop

DIAGNOSTICO-MANTIS (contexto)
       ↓
       Usado para validar que se cumple ROI prometido
```

---

## Status

**Arquitectura**: ✅ Definida
**Detalles**: ⏳ Pendiente desarrollo
**Prompts**: ⏳ Pendiente desarrollo

---

**Versión**: 0.1 | **Estado**: Base Architecture | **Fecha**: 2026-06-22
