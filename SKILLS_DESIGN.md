# SKILLS_DESIGN.md — Diseño de Skills Zapier MCP

## Instrucciones

Antes de implementar cada skill, responde estas tres preguntas:

1. **¿Qué hace esta skill?** Una frase.
2. **¿Qué input necesita el agente?** ¿Qué le das, en qué formato — y qué ya sabe?
3. **¿Cómo es un buen output?** Formato, destino y cómo sabrás que funcionó.

---

## Skill 1 — Plan Semanal

### 1. ¿Qué hace esta skill?

Dado un listado de objetivos y compromisos para la semana, el agente escribe un plan semanal priorizado en un Google Doc nuevo y crea los eventos clave en Google Calendar con bloques de tiempo dedicados.

### 2. ¿Qué input necesita el agente?

- **Input del usuario:** una lista en lenguaje natural de objetivos, tareas y compromisos para la semana (ej: "tengo que entregar el informe de ventas, preparar la presentación del jueves, llamar al cliente el miércoles, y estudiar 4 horas esta semana").
- **Contexto que ya tiene el agente:** las conexiones activas de Zapier (Google Docs, Google Calendar, Gmail), la fecha actual, y el workspace del proyecto.
- **Formato:** texto libre en lenguaje natural.

### 3. ¿Cómo es un buen output?

1. **Google Doc** creado con título "Plan Semanal — [fecha inicio]" que contiene:
   - Resumen de la semana
   - Objetivos priorizados
   - Desglose día por día con tareas específicas
   - Checklist de pendientes
2. **Eventos en Google Calendar** creados automáticamente para las tareas principales con bloques de tiempo realistas.
3. **(Opcional)** Correo de resumen enviado al usuario vía Gmail.
4. El usuario confirma que el plan refleja sus prioridades y los eventos están en su calendario.

---

## Skill 2 — [Nombre de la skill]

### 1. ¿Qué hace esta skill?



### 2. ¿Qué input necesita el agente?



### 3. ¿Cómo es un buen output?



---

## Skill 3 — [Nombre de la skill]

### 1. ¿Qué hace esta skill?



### 2. ¿Qué input necesita el agente?



### 3. ¿Cómo es un buen output?