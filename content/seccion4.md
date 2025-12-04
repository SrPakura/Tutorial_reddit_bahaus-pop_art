## 4\. Estrategia "Hacker": Automatización con Python y Gemini

¿Queréis hacerlo de lujo y que el karma venga solo? Os presento a vuestros mejores amigos: **Python** y **Google AI Studio**.  

Ojo, no hagáis automatización completa (bots 100%) porque Reddit (y cualquier página que se digne) lo detecta, y os banea desde la IP hasta el DNI. Haremos un sistema "Cyborg": la máquina busca, tú disparas.  

**El flujo de trabajo:**

1. **El Ojeador (Python \+ Gemini 2.5 Flash):**  
   * Hacéis un script en Python (tanto gemini como chatgpt saben hacerlo) que recargue la página de "New" cada minuto (usad atajos de teclado, no clics del ratón, para parecer humanos).  
   * El script hace una captura de pantalla.  
   * Envía la captura a la API de **Gemini 2.5 Flash** (es gratis y rápida).  
   * **Prompt:** *"Califica estos hilos del 1 al 10 según la probabilidad de que se hagan virales en 24h. Sé conservador. Formato: (1, 9, 2, 4...)"*.  
2. **El Chivato (Telegram):**  
   * Si el script ve un número igual o mayor a **8**, te manda un mensaje a tu Telegram con el enlace.  
3. **El Francotirador (Tú \+ Gemini 2.5 Pro/3.0 Pro):**  
   * Te llega la notificación. Pausas el script (importante, o seguirás gastando peticiones).  
   * Vas a **Google AI Studio** y usas un modelo más potente y creativo (**Gemini 2.5 Pro** o el **3.0**).  
   * **Prompt:** *"Tu tarea es hacer reír a unos redditors cínicos para ganar upvotes. Genera una respuesta ingeniosa, sarcástica o un juego de palabras para este post"*.  
   * Copias la respuesta (revisad que no suene a robot y que esté en inglés), la pegáis y reactiváis el script.

¡Ea\! A dejar que el karma suba como la espuma. Con 50-100 de karma, tenéis suficiente para no parecer un bot, pasar requisitos mínimos de Karma, y spamear vuestras preguntas para la netnografia.  
