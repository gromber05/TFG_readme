# Delvo

##1. ¿De qué va el proyecto?**Delvo** es un ecosistema de productividad diseñado para actuar como un **Asistente Personal Inteligente**. Su objetivo principal es ayudar a los usuarios a organizar su vida diaria mediante la gestión de tareas, notas, eventos y rutinas, pero con un valor añadido: **la Inteligencia Artificial**.

A diferencia de una lista de tareas normal, Delvo utiliza un módulo de IA para:

* Aprender de tus hábitos.
* Clasificar tareas automáticamente.
* Sugerir planificaciones semanales.
* Detectar en qué momentos del día eres más productivo.

##2. Estructura Técnica (¿En qué consiste?). El proyecto está diseñado como un **Monorepo** (un solo repositorio que contiene todo) y se divide en tres partes principales que se sincronizan en tiempo real:

###📱 Aplicación Móvil (Android)* **Tecnología:** Kotlin y Jetpack Compose.
* **Función:** Es la herramienta de uso diario. Permite ver el resumen "Hoy", crear tareas rápidas por voz o texto y recibir notificaciones inteligentes.

###💻 Aplicación Web* **Tecnología:** Angular o React (según decidas finalmente).
* **Función:** Panel de control avanzado (Dashboard). Aquí verás estadísticas, gráficos de productividad, gestión de hábitos y resúmenes semanales generados por la IA.

###⚙️ Backend (El cerebro)* **Tecnología:** Spring Boot (Kotlin) y base de datos PostgreSQL.
* **Función:** Gestiona toda la lógica, la seguridad (JWT), la base de datos y conecta los servicios de IA con las aplicaciones (móvil y web).
