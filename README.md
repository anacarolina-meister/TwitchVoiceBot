# Twitch TTS Bot 

Aplicación en Java diseñada para interactuar con los directos de Twitch. Permite a los espectadores canjear puntos del canal para reproducir mensajes de texto a voz (TTS) utilizando voces personalizadas mediante IA.

## Tecnologías y Herramientas
* **Lenguaje:** Java
* **Integración Twitch:** Twitch4J
* **Generación de Voz (TTS):** API de ElevenLabs
* **Entorno de Desarrollo:** IntelliJ IDEA

## Arquitectura del MVP (Producto Mínimo Viable)
1. Conexión de lectura con los eventos de Twitch.
2. Intercepción del evento de canjeo de puntos y extracción del mensaje.
3. Llamada HTTP a la API de ElevenLabs con el texto.
4. Descarga y reproducción automática del archivo de audio resultante.