#  Informe Técnico – Evaluación de Cumplimiento Normativo

## 1. Introducción

El presente informe documenta el análisis de cumplimiento normativo realizado sobre el sistema operativo y tecnológico de **Bray Controls Andina**, empresa del sector industrial enfocada en la gestión de válvulas, automatización y procesos comerciales.

El objetivo principal del taller fue evaluar el nivel de cumplimiento en aspectos legales, de seguridad de la información y operación, identificando brechas y riesgos asociados. Para ello, se tomaron como referencia marcos normativos y buenas prácticas como:

- Ley 1581 de 2012 (Protección de Datos Personales – Colombia)  
- Principios de Habeas Data  
- Estándar internacional ISO/IEC 27001  

El análisis se centró en los procesos críticos del negocio, desde la gestión de órdenes de venta hasta el despacho de productos, permitiendo identificar debilidades estructurales y oportunidades de mejora.

---

## 2. Contexto del sistema analizado

El sistema evaluado soporta el flujo operativo principal de la organización:

**Sales Order → Planeación → Compras → Inventario → Despacho**

Este flujo involucra múltiples áreas y herramientas tecnológicas, siendo fundamentales para el cumplimiento de pedidos y la operación logística.

### Componentes principales:

- ERP LN (gestión de órdenes, compras e inventario)  
- Dynamics 365 (gestión comercial y cotizaciones)  
- Microsoft Excel (soporte operativo y análisis)  
- Sistemas de bodega (gestión física de inventario)  
- Herramientas de comunicación (Outlook)  

Estos componentes presentan un nivel de integración funcional, pero con dependencia significativa de procesos manuales.

---

## 3. Metodología

El desarrollo del taller se realizó en cinco etapas:

1. Levantamiento de información mediante entrevistas y observación de procesos.  
2. Identificación de procesos críticos del negocio.  
3. Construcción de un checklist de cumplimiento normativo.  
4. Evaluación de cada criterio según niveles de cumplimiento (✅, ⚠️, ❌).  
5. Identificación de brechas, riesgos y oportunidades de mejora.  

La información fue estructurada en herramientas como Excel, combinando análisis cualitativo con criterios basados en estándares internacionales.

---

## 4. Modelo de evaluación

El modelo propuesto se basa en una evaluación estructurada por categorías:

- Datos personales  
- Seguridad de la información  
- Gestión de la información  
- Operación  
- Cumplimiento normativo  

Cada categoría incluye:

- Criterios de evaluación  
- Nivel de cumplimiento  
- Evidencia identificada  
- Recomendaciones  

Este enfoque permite una visión integral del estado actual del sistema frente a buenas prácticas.

---

## 5. Resultados del análisis

### 5.1 Datos personales

Se identificó que la organización maneja datos de clientes; sin embargo:

- No hay evidencia clara de políticas de retención y eliminación  
- No se documentan mecanismos para garantizar derechos del titular  
- No existe trazabilidad completa del uso de datos  

Esto representa un riesgo de incumplimiento de la Ley 1581.

---

### 5.2 Seguridad de la información

Se evidenciaron controles básicos, pero con debilidades importantes:

- Gestión de accesos no completamente documentada  
- Ausencia de políticas formales de seguridad  
- Dependencia del conocimiento operativo de los usuarios  

---

### 5.3 Gestión de la información

El uso de múltiples herramientas genera:

- Duplicidad de información  
- Inconsistencias en datos  
- Falta de centralización  

Especialmente por el uso intensivo de Excel en procesos críticos.

---

### 5.4 Operación

Se identificaron limitaciones operativas como:

- Procesos manuales en planeación y despacho  
- Falta de trazabilidad en órdenes  
- Problemas de visibilidad en tiempo real  

Esto impacta la eficiencia y control del sistema.

---

### 5.5 Cumplimiento normativo

El análisis evidenció:

- Falta de formalización de procesos  
- Ausencia de documentación estructurada  
- Dependencia de prácticas informales  

Lo que dificulta auditorías y control organizacional.

---

## 6. Principales brechas identificadas

A partir del análisis, se identificaron las siguientes brechas críticas:

- Dependencia de procesos manuales (Excel)  
- Falta de trazabilidad en operaciones  
- Ausencia de políticas de datos personales  
- Gestión de accesos no formalizada  
- Falta de centralización documental  
- Baja integración entre sistemas  

Estas brechas representan riesgos tanto operativos como legales.

---

## 7. Supuestos del análisis

Para el desarrollo del modelo se consideraron los siguientes supuestos:

- El ERP LN es el sistema central, pero no cubre completamente la operación  
- El uso de Excel introduce riesgos de control y seguridad  
- No existe un sistema formal de gestión de seguridad de la información  
- La empresa maneja datos personales, implicando cumplimiento obligatorio  

---

## 8. Propuestas de mejora

Se proponen las siguientes acciones:

- Definir políticas de tratamiento de datos personales  
- Implementar gestión formal de accesos (roles y permisos)  
- Reducir dependencia de Excel mediante automatización  
- Centralizar la documentación organizacional  
- Implementar trazabilidad completa de procesos  
- Adoptar un enfoque basado en ISO/IEC 27001  

---

## 9. Buenas prácticas recomendadas

Se recomienda la adopción de:

- Sistema de Gestión de Seguridad de la Información (SGSI)  
- Principio de mínimo privilegio  
- Auditoría y monitoreo continuo  
- Gestión de incidentes de seguridad  
- Mejora continua basada en riesgos  

---

## 10. Conclusión

El análisis permitió identificar que, aunque la organización cuenta con herramientas tecnológicas robustas, presenta debilidades en la gestión, control y formalización de procesos.

Los principales riesgos se concentran en:

- Procesos manuales  
- Falta de trazabilidad  
- Gestión de accesos  
- Cumplimiento normativo  

La implementación de mejoras estructurales permitirá fortalecer la seguridad, optimizar la operación y garantizar el cumplimiento legal, alineando el sistema con estándares internacionales y buenas prácticas.

---

## 11. Referencias

1. Ley 1581 de 2012 – Protección de Datos Personales (Colombia)  
2. ISO/IEC 27001 – Information Security Management  
3. Habeas Data – Marco constitucional colombiano  
4. OMG. Business Process Model and Notation (BPMN)  
   https://www.omg.org/spec/BPMN/  
