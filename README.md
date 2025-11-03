# 👑 EL BUHO 89 Bot Modular: La Solución Inestable (pero Elegante) ☕

### 🎭 El Dramático Propósito de Este Repositorio

Bienvenidos a esta pequeña joya del *software* que, francamente, es demasiado buena para ser gratuita, pero aquí está. Esto no es un simple juguete de fin de semana; es un **Framework de Código Abierto** (sí, reutilizable, pero *léase la licencia*) diseñado para que los humanos dejen de sufrir con la comunicación en Telegram. Combina la frialdad de la **Inteligencia Artificial** con la torpeza esencial de la atención **humana**, todo orquestado desde un solo archivo HTML.

Si odias los *microservicios* y amas el drama de tener **toda la lógica en una sola pestaña del navegador**, este es tu lugar.

---

## 📁 Estructura del Proyecto y Archivos Especiales

El proyecto está autocontenido en un solo archivo para máxima simplicidad.

| Archivo | Descripción |
| :--- | :--- |
| `index.html` | Contiene todo el HTML, CSS (`<style>`) y JavaScript (`<script>`). **Es el núcleo del sistema.** |
| `README.md` | El archivo que estás leyendo ahora (la introducción al drama). |
| [`LICENSE`](./LICENSE) | Contiene los términos completos de la **Licencia CC BY-NC-SA 4.0**. |
| [`MISTEREGG.md`](./MISTEREGG.md) | **La Tradición de la Medianoche.** Anécdotas, frases y frustraciones del desarrollador. **¡Lectura obligatoria!** |

---

### ⚠️ Advertencia Crucial: No Culpes al Universo (Culpa a tu Navegador)

Escucha con atención, mortal, porque esto es importante: **Este sistema opera mediante Polling**. Esto significa que es tan estable como mi conexión WiFi en hora pico y tan confiable como una promesa en Internet.

> **¡Si cierras la pestaña o el navegador, la ejecución se detiene. PUNTO\!** No esperes un servicio 24/7. Esto no es una promesa, es un descargo de responsabilidad con sabor a café amargo.

---

### ✨ Características (Demasiado) Útiles

* **Panteón de IAs Conectadas:** Hemos integrado soporte configurable para los grandes dioses de la inteligencia: **Google Gemini**, **OpenAI ChatGPT**, y el intrigante **Perplexity**. O, por si eres un purista masoquista, puedes desactivarla por completo.
* ***Handoff* Dramático:** La IA, con su infinita sabiduría (o por una palabra clave como "¡Agente!", "humano", "asesor"), transferirá la conversación a los humanos. Es un pase de batón elegante del silicio a la carne.
* **Memoria (Corto Plazo):** Usa **Firebase Firestore** para recordar conversaciones. Si no lo configuras, tendremos que sufrir el modo "en memoria", donde la IA olvida tu existencia al recargar la página. ¡Elige tu nivel de drama!.
* **Anti-Spam para los Elegantes (reCAPTCHA):** Sí, incluso aquí necesitamos un poco de seguridad. Incluimos el código de reCAPTCHA para que los bots genéricos y el spam no nos arruinen la fiesta digital. **Necesitas tu propia clave de sitio** para que la magia funcione en tu dominio, la que ves es solo un *placeholder* para demostrar que existe.

---

### 🛠️ Ritual de Configuración (No Te Equivoques)

1.  **El Token Sagrado:** Consigue tu `Token de Bot` con el todopoderoso [@BotFather].
2.  **Las Identidades Secretas:** Obtén los `Chat IDs` de los asesores. Si usas un grupo, recuerda, el ID será un número **negativo** (como el saldo de mi cuenta bancaria).
3.  **La Clave del Silicio:** Proporciona la **Clave API** de la IA que hayas elegido. Sin ella, la IA es solo un fantasma elegante.
4.  **Despliegue y Sufrimiento:** Sube el glorioso `index.html` a algún lugar donde el JavaScript pueda correr libremente (GitHub Pages funciona, pero el Polling es tu responsabilidad).

---

### 🗣️ Comandos para Asesores (Para que no Llores)

Los asesores no tienen que ser elegantes, solo eficientes. Desde el chat de soporte, pueden:

* **Responder:** `/CHATID tu respuesta aquí` (Reemplaza `CHATID` con el ID del cliente).
* **Tomar Posesión:** `/take CHATID` (Para asignarse un chat de un grupo).
* **Cerrar el Drama:** `/close CHATID` (Devuelve el control a la IA. ¡Paz!).

---

### 📜 Licencia: Sí, Hay Reglas

Este código se distribuye bajo la licencia **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

En términos humanos y sencillos:

* **Puedes usarlo y modificarlo.**
* **Debes dar crédito** (¡Atribución!).
* **No puedes lucrar con él** (No Comercial. Sí, leíste bien. El dinero es vulgar).
* Cualquier derivado debe mantener esta misma licencia (Compartir Igual).

Si vienes a hacer dinero, elige otra licencia; esta es para el arte.
Para más detalles, consulta el archivo [`LICENSE`](./LICENSE).
