#  Instagram Lite – Proyecto de Testing QA

## QA Analyst
Ailín Arias

---

##  Descripción del Proyecto

Este proyecto consiste en la ejecución completa de un proceso de **Testing Funcional Manual** sobre la aplicación **Instagram Lite**, versión optimizada de Instagram desarrollada por Meta.

El trabajo incluyó:

- Análisis de requerimientos
- Diseño de épicas e historias de usuario
- Definición de criterios de aceptación
- Diseño y ejecución de casos de prueba positivos y negativos
- Identificación y clasificación de defectos
- Análisis de métricas de calidad
- Testing de API REST utilizando Postman

El objetivo fue simular un proceso profesional de QA siguiendo buenas prácticas de la industria.

---

## Objetivo del Testing

Validar que la aplicación cumpla con los requisitos funcionales definidos en los principales flujos de usuario, asegurando:

- Correcto funcionamiento de los módulos críticos
- Validaciones adecuadas de datos
- Consistencia en la experiencia de usuario
- Identificación de defectos
- Evaluación de preparación para producción

---

## Alcance del Testing

El alcance se organizó en dos épicas principales:

### Épica 1 – Gestión y Autenticación de Sesión
- Registro de usuario (correo y teléfono)
- Inicio de sesión
- Cierre de sesión
- Recuperación de contraseña

### Épica 2 – Gestión de Contenido
- Publicar contenido
- Editar publicaciones
- Eliminar publicaciones
- Visualizar publicaciones propias
- Interactuar con publicaciones propias (likes y comentarios)

Se diseñaron y ejecutaron un total de **32 casos de prueba funcionales**, incluyendo escenarios positivos y negativos.

---

##  Entorno de Prueba

- Aplicación bajo prueba: Instagram Lite
- Tipo de testing: Manual – Funcional
- Herramientas utilizadas:
  - Excel (diseño y ejecución de casos de prueba)
  - Postman (Testing de API REST – Fake Store API)
  - GitHub (control de versiones y documentación)

---

## Resumen de Ejecución

| Estado              | Cantidad | Porcentaje |
|---------------------|----------|------------|
| Casos Correctos     | 25       | 78,1%      |
| Observaciones       | 4        | 12,5%      |
| Defectos Detectados | 3        | 9,4%       |
| Defectos Críticos   | 0        | 0%         |

No se detectaron fallas bloqueantes ni pérdida de datos.

---

## Análisis de Defectos

### Severidad Alta (33%)
- Validación de contraseña insuficiente: no exige combinación alfanumérica aunque el sistema lo indica.  
  Impacto: Seguridad.

### Severidad Media (67%)
- El contador de comentarios no se actualiza automáticamente.
- Inconsistencia en la actualización entre contador de “me gusta” y comentarios.  
  Impacto: Experiencia de usuario / Consistencia visual.

No se identificaron defectos críticos.

---

## Evaluación de Calidad

La aplicación demostró:

✔ Estabilidad funcional en flujos principales  
✔ Correcta validación de campos obligatorios  
✔ Gestión adecuada de contenido  
✔ Ausencia de errores críticos o bloqueantes  

Se identificaron oportunidades de mejora en:

- Validaciones de seguridad
- Consistencia en la retroalimentación visual de interacciones

---

##  Conclusión Final

En base a los casos ejecutados y al análisis realizado, Instagram Lite presenta un alto nivel de estabilidad funcional.

Los defectos detectados no comprometen la operatividad general del sistema. Desde el punto de vista funcional evaluado, el producto puede considerarse **apto para producción**, recomendando implementar mejoras menores en validaciones de seguridad y experiencia de usuario.

---

##  Estructura del Repositorio

- `/Casos de Prueba` → Diseño y ejecución de pruebas funcionales  
- `/Testing API` → Casos y resultados de pruebas REST  
- `/Informe` → Informe final y resumen ejecutivo  
- `/Evidencias` → Capturas y documentación de soporte  

---

## Competencias Demostradas

- Análisis de requerimientos
- Diseño de casos de prueba
- Testing funcional manual
- Escenarios positivos y negativos
- Reporte y clasificación de defectos
- Análisis de métricas
- Testing de API REST con Postman
- Documentación profesional de QA

---

📌 Este proyecto representa una simulación integral de un proceso de Testing QA siguiendo estándares profesionales.
