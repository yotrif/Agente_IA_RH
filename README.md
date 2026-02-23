 # Asistente Virtual de RRHH — Agente IA en n8n

Este repositorio contiene un flujo de trabajo de un asistente de Recursos Humanos impulsado por IA construido en **n8n** usando un modelo de lenguaje vía OpenRouter.

---

##  Descripción General

Este workflow simula un asistente corporativo de RRHH capaz de:

* Asistencia en acontecimientos laborales
* Evaluar candidatos para una vacante
* Gestionar solicitudes de carta laboral y desprendible de pago
* Aplicar políticas de privacidad
* Escalar casos sensibles a un analista humano

---

##  Arquitectura

**Disparador:** Mensaje de chat
**Modelo IA:** Mixtral-8x7B (OpenRouter)
**Tipo de Agente:** LangChain Agent
**Plataforma de Automatización:** n8n

---

##  Archivo

`My workflow (1).json` → Importa este archivo directamente en n8n para ejecutar el agente.

---

##  Cómo usarlo

1. Abre n8n
2. Haz clic en **Import Workflow**
3. Pega el enlace RAW del JSON de este repositorio
4. Activa el workflow
5. Empieza a chatear con el agente

---

##  Capacidades del Agente

### Información de RRHH

Responde únicamente usando datos definidos en el manual empleado simulado.

### Evaluación de Candidatos

Verifica:

* Años de experiencia
* Nivel de Excel

Y determina si el candidato cumple los requisitos para el puesto de Analista de Datos.

### Protección de Privacidad

Si un usuario solicita datos sensibles, el agente responde:

> "Lo siento, debido a políticas de privacidad, solo puedo proporcionar información sobre tu propio perfil."

### Protocolo de Escalamiento

Si la conversación incluye:

* temas legales
* acoso laboral
* discriminación
* quejas formales

El agente escala inmediatamente a un analista humano.

---

##  Objetivo del Proyecto

Este proyecto demuestra:

* Diseño de agentes de IA
* Ingeniería de prompts
* Automatización de flujos
* Control lógico conversacional

---

##  Autor

Desarrollado por **Samuel**
Ingeniería en Analítica de Datos

---

##  Licencia

Proyecto con fines educativos y demostrativos.
