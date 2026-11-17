# Nexus

![TFG](https://img.shields.io/badge/TFG-2º%20DAW-blue)
![Estado](https://img.shields.io/badge/Estado-Finalizado-success)

Asistente con IA para la web del CPIFP Los Enlaces. Los visitantes le preguntan sus dudas desde un chat integrado en la web del centro, y responde usando RAG sobre la documentación del centro (ciclos, secretaría, servicios…). Desde un panel de administración se pueden revisar las conversaciones, gestionar los documentos de la base de conocimiento y configurar el asistente.

## Tecnologías

![Tecnologías](https://skillicons.dev/icons?i=js,vue,tailwind,nodejs,express,supabase)

## Repositorios

| Parte | Descripción | Repositorio |
|---|---|---|
| API | Recibe los mensajes, busca los fragmentos de documentación más relevantes y genera la respuesta con OpenAI. También gestiona los documentos, el feedback y la configuración. | [PI_NexusBackend](https://github.com/rsvisu/PI_NexusBackend) |
| Widget de chat | Se incrusta en la web del centro con una sola etiqueta `<script>`. El usuario acepta el tratamiento de sus datos, pregunta y puede valorar cada respuesta o borrar su conversación. | [PI_NexusWidget](https://github.com/rsvisu/PI_NexusWidget) |
| Panel de administración | Permite ver las conversaciones y métricas, subir y organizar los documentos por carpetas, revisar el feedback negativo y cambiar la configuración del asistente. | [PI_NexusDashboard](https://github.com/rsvisu/PI_NexusDashboard) |
