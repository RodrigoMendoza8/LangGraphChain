Este repositorio es un espacio personal dedicado al aprendizaje y experimentación con el ecosistema de LangChain, LangGraph y el despliegue de aplicaciones de IA generativa. El objetivo es documentar mi progreso a medida que exploro desde los conceptos básicos hasta arquitecturas de agentes complejas.

🚀 Tecnologías Utilizadas
El proyecto utiliza las siguientes herramientas y librerías principales:

Python: >= 3.14

LangChain: Framework para el desarrollo de aplicaciones impulsadas por modelos de lenguaje.

OpenAI: Integración con modelos como gpt-4o-mini y gpt-4.

Streamlit: Para la creación de interfaces de usuario interactivas.

LangGraph: Para la gestión de flujos de trabajo cíclicos y estados.

📚 Contenido por Temas
Tema 1: Fundamentos de LangChain y Chatbots
En este primer módulo, me enfoqué en establecer la base de la comunicación con LLMs y la estructuración de prompts.

Conceptos clave aplicados:

Configuración de LLM: Implementación de modelos de chat (OpenAI) ajustando parámetros como temperature para controlar la creatividad de las respuestas.

Prompt Templates: Uso de PromptTemplate para crear estructuras de mensajes reutilizables y dinámicas, permitiendo inyectar variables como nombres de usuario o historiales de conversación.

LCEL (LangChain Expression Language): Uso de la sintaxis de "pipes" (|) para encadenar plantillas con modelos de lenguaje de forma eficiente.

Gestión de Historial: Implementación de memoria básica utilizando HumanMessage y AIMessage para mantener el contexto de la charla.

Interfaces con Streamlit: Creación de un chatbot funcional ("RorroBot") que permite ajustar el modelo y la temperatura en tiempo real desde una barra lateral.

Instalar dependencias:
Este proyecto utiliza uv para la gestión de paquetes:

Bash
uv sync
Variables de Entorno:
Configurar la API KEY de chat gpt para que funcionen las llamadas, esto lo realicé desde la terminal utilizando el siguiente comando.

```bash
setx OPENAI_API_KEY "Tu Api_key"