# Cimenta — Herramienta de Monitoreo de Carga Laboral en RRHH

**Ramo:** Gestión de Personas y Comportamiento Organizacional  
**Universidad:** Universidad de Concepción — Departamento de Ingeniería Industrial  
**Semestre:** 2025-1  
**Integrantes:** Juan Pablo García Duhalde · Sebastián Rosales Carrasco · Mateo Parra Mena · Alan Wilson Germany  
**Empresa estudiada:** Cimenta S.A. — Administradora General de Fondos, Santiago de Chile  
**Fecha de entrega:** 7 de julio de 2025

---

## Descripción del Proyecto

Trabajo semestral de consultoría aplicada en gestión de personas. El equipo diagnosticó los procesos de RRHH de **Cimenta S.A.**, empresa inmobiliaria fundada en 1991 con patrimonio superior a UF 8.227.902 y 51 colaboradores en su oficina central. A partir del diagnóstico se identificó el problema prioritario y se diseñó, prototipó y validó una solución directamente con la empresa.

**Descripción de la empresa:**
- Administradora General de Fondos con estructura de holding (6 empresas)
- Enfoque en renta inmobiliaria: oficinas, bodegas, locales, hostelería y residencias especializadas
- Equipo profesional: ingenieros, abogados, contadores y analistas
- 51 trabajadores en oficina central — 64% masculino / 36% femenino
- Baja rotación, sin sindicato, código de ética formal

---

## Problema Identificado

**Desequilibrio entre vida laboral y personal** (puntaje multicriterio: 8,1 vs. 7,6 del segundo problema).

El problema se manifiesta en jornadas extendidas, disponibilidad permanente fuera del horario laboral y picos críticos de carga en los cierres mensuales de directorios. Las causas raíz identificadas son:

- Ausencia de una gerencia de RRHH especializada (depende de Control de Gestión y Back Office)
- Falta de estimaciones formales de tiempo por tarea
- Baja claridad en la priorización de tareas durante cierres
- Monitoreo insuficiente de la carga laboral real

**Evidencia:** Evaluaciones psicosociales con nivel de riesgo **alto** en las dimensiones *Exigencias Emocionales* y *Equilibrio trabajo-vida privada*, respaldadas por entrevistas al equipo de Capital Humano.

---

## Alternativas Evaluadas

| # | Solución | T. Implement. | Impacto | Costo | Viabilidad | **Puntaje** |
|---|----------|:---:|:---:|:---:|:---:|:---:|
| 1 | **Planilla Excel de monitoreo de carga laboral** | 9 | 9 | 8 | 8 | **8,55** ✅ |
| 2 | Política de desconexión digital | 7 | 6 | 9 | 7 | 7,10 |
| 3 | Capacitación en gestión del tiempo | 7 | 8 | 7 | 8 | 7,55 |
| 4 | Charlas de bienestar emocional | 7 | 6 | 7 | 7 | 6,70 |

*Ponderaciones: Tiempo de implementación 25% · Impacto en productividad 30% · Costo 20% · Viabilidad práctica 25%.*

---

## Solución: Herramienta Excel de Monitoreo de Carga Laboral

### Descripción

Planilla Excel estructurada en tres hojas que permite registrar, distribuir y visualizar la carga de trabajo de cada colaborador, con un horizonte de 12 semanas (3 meses).

### Arquitectura de la herramienta

| Hoja | Función |
|------|---------|
| **Registro** | Ingreso de tareas: empleado, actividad, fecha de inicio, plazo, horas estimadas y estado (Vigente/Terminado) |
| **Carga de HH** | Distribución automática de horas por semana y por persona. No debe modificarse manualmente. |
| **Gráficos HH** | Dashboard visual con tablas y gráficos de carga por empleado, por semana y proyección acumulada. Se actualiza con *Datos > Actualizar todos*. |

### Datos del prototipo

- **Empleados:** 7 colaboradores del área de Capital Humano
- **Total HH registradas:** ~374 horas-hombre en el horizonte de 3 meses
- **Actividades registradas:** Reclutamiento y selección, Inducción, Administración de personal, Gestión de remuneraciones, Capacitación y desarrollo, Evaluación del desempeño, Gestión del clima laboral, Gestión de conflictos, Salud y seguridad, Cumplimiento legal, Comunicación interna, Monitoreo de carga laboral

### Mejoras incorporadas tras el feedback de la empresa

La empresa validó el prototipo positivamente y solicitó incorporar gráficos automáticos para una lectura más visual. Se agregaron:

1. Gráfico de carga laboral total por empleado (barras)
2. Gráfico de tendencias semanales de distribución de HH
3. Gráfico de carga proyectada acumulada por empleado

---

## Archivos del Repositorio

| Archivo | Descripción |
|---------|-------------|
| `Informe-Final-Grupo-09-Cimenta.pdf` | Informe completo: diagnóstico, análisis, propuestas y evaluación multicriterio |
| `Grupo-09-CIMENTA.pdf` | Presentación ejecutiva del proyecto |
| `Gestion-de-Horas.xlsx` | Prototipo funcional de la herramienta Excel con datos de ejemplo y gráficos |

---

## Conclusiones

El diagnóstico reveló que Cimenta cuenta con buenas prácticas en remuneraciones y beneficios, pero enfrenta brechas importantes en la formalización de sus procesos de RRHH. La herramienta desarrollada aborda la raíz del problema —la falta de visibilidad sobre la carga real— con una solución de bajo costo, rápida implementación y alta viabilidad práctica. La empresa recibió el prototipo positivamente, validando su pertinencia para el contexto organizacional.
