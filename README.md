# ⚠️📊Detección de Anomalías de Riesgo por Evento

## 📌Descripción del proyecto

Este proyecto implementa una consulta SQL para detectar anomalías de riesgo asociadas a eventos específicos, permitiendo analizar cómo determinados eventos impactan el perfil de riesgo de entidades, activos o procesos.

El objetivo es identificar comportamientos atípicos posteriores a un evento relevante, facilitando la detección temprana de riesgos emergentes y efectos no esperados.

## 🎯Objetivos del proyecto

- Analizar el impacto de eventos críticos sobre métricas de riesgo.
- Detectar anomalías posteriores al evento.
- Comparar comportamiento pre y post evento.
- Identificar eventos con impacto sistémico.
- Automatizar el monitoreo de riesgo mediante SQL.

## 🏦Contexto de negocio

En entornos financieros y corporativos, ciertos eventos (downgrades, crisis, fallas operativas, cambios regulatorios) pueden generar incrementos abruptos de riesgo.

📌 No todos los impactos son inmediatos ni evidentes.

Detectar anomalías post-evento permite:
- Anticipar deterioros futuros
- Priorizar acciones de mitigación
- Mejorar modelos de stress y control
- Este análisis es clave para:
- Gestión de riesgo
- Finanzas
- BI & Analytics
- Auditoría
- Compliance

## 🧠Lógica del análisis

La consulta SQL:
- Identifica eventos relevantes y su fecha.
- Define ventanas temporales pre y post evento.
- Calcula métricas de riesgo (volatilidad, spreads, desviaciones, pérdidas).

Compara valores contra:
- Histórico
- Umbrales definidos
- Comportamiento esperado
- Marca anomalías cuando el riesgo se desvía significativamente tras el evento.

📌 El enfoque es adaptable a distintos tipos de eventos y métricas.

## 📊Ejemplos de anomalías detectadas

- Incremento abrupto de volatilidad post-evento.
- Deterioro persistente de métricas de riesgo.
- Reacciones desproporcionadas frente a eventos menores.
- Diferencias de impacto entre sectores o regiones.

## 🛠️Tecnologías utilizadas

SQL

Compatible con:
- PostgreSQL
- BigQuery
- SQL Server
- Oracle
- MySQL (con ajustes menores)

## 📁Estructura del proyecto

├── Anomalias_riesgo_por_evento.sql
└── README.md

## ▶️Cómo utilizar la consulta

Abrir el archivo Anomalias_riesgo_por_evento.sql.

Configurar:
- Tabla de eventos
- Métricas de riesgo
- Ventanas temporales
- Umbrales de anomalía
- Ejecutar la consulta en el motor SQL.
- Integrar resultados en reportes, dashboards o sistemas de alerta.

## 🚀Posibles extensiones

- Clasificar anomalías por severidad.
- Analizar múltiples eventos encadenados.
- Incorporar benchmarks sectoriales.
- Automatizar alertas post-evento.
- Integrar con modelos predictivos de riesgo.

## 👤Autora

Flavia Hepp
Proyecto de SQL aplicado a análisis de riesgo basado en eventos.
