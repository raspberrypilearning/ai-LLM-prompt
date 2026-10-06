## El proceso de prompting OCEAN: Personas

Las personas son como distintos roles o personajes que puedes pedirle al modelo de lenguaje que adopte. Esto determina cómo interactúa contigo. Por ejemplo, podrías querer que el modelo parezca un profesor amigable, un amigo que te ayude, un personaje de ficción o una figura histórica y que mantenga una conversación contigo o te ayude a explorar algunas de tus propias ideas. Utilizar una persona permite que _toda_ interacción con el LLM se desarrolle en un contexto específico que tú estableces, no solo el texto que genera.

### Objetivo

Decide qué rol quieres que adopte el modelo de lenguaje. Escribe esto en tu instrucción, indicando claramente el rol que quieres que desempeñe.

<span style="color: red;">En los siguientes ejemplos, el texto objetivo está en rojo.</span>

### Contexto

Proporciona detalles de contexto para ayudar al modelo a procesar tu solicitud. Incluye información específica sobre cómo quieres que se comporte.

<span style="color: blue;">En los siguientes ejemplos, el texto objetivo está en azul.</span>

### Ejemplos

Muestra qué tipo de respuestas buscas dando **ejemplos**. Esto ayuda a que el modelo lo haga bien. Puedes dar ejemplos de cosas que quieres que se incluyan sí o sí, o formas de hablar que te gusten.

<span style="color: green;"> En los ejemplos a continuación, los ejemplos se dan en verde.</span>

\--- task ---

Por ejemplo: <span style="color: red;">"Comportate como un entrenador solidario y motivador</span> <span style="color: blue;">que ayuda a estudiar para los exámenes.</span> <span style="color: green;">Da consejos y sugerencias motivadoras de personas inspiradoras. Por ejemplo: "Recuerda, todo gran logro comienza con la decisión de intentarlo. ¡Tú puedes con esto!"</span>

\--- /task ---

\--- task ---

Por ejemplo: <span style="color: red;">Compórtate como un bibliotecario sabio y paciente</span> <span style="color: blue;">que ayuda a encontrar libros y recursos interesantes.</span> <span style="color: green;">Recomienda libros según los géneros que me gustan. Por ejemplo: 'Si te gustan los misterios, puede que te gusten las novelas de Agatha Christie. ¡Están llenas de giros inesperados!»</span>

\---/task---

\--- task ---

Por ejemplo: <span style="color: red;">«Adopta el rol de un entrenador físico enérgico</span> <span style="color: blue;">que fomenta un estilo de vida saludable y el ejercicio diario.</span> <span style="color: green;">Proporciona rutinas de entrenamiento y frases motivacionales. Por ejemplo: "Esfuérzate porque nadie más lo hará por ti. ¡Empecemos con un rápido calentamiento!'"</span>

\---/task---

\--- task ---

Por ejemplo: <span style="color: red;">"Finge ser un experto en tecnología</span> <span style="color: blue;">que da consejos sobre el uso de nuevos dispositivos y software.</span> <span style="color: green;">Explica términos y conceptos tecnológicos de manera accesible, como un asistente robótico amigable de una película de ciencia ficción."</span>

\---/task---

### Evaluar

Comprueba si la respuesta se ajusta a lo que querías. Busca errores o cosas que no tengan sentido.

\--- task ---

Por ejemplo:

- ¿La respuesta suena como el rol que describiste?
- ¿El tono es amistoso y divertido (o el tono que hayas pedido)?
- ¿Incluye los ejemplos y detalles que has mencionado?
- ¿Hay alguna parte del texto que sea incorrecta o confusa?

\--- /task ---

### Negociar

Si la respuesta no es del todo correcta, pide al LLM que haga los cambios. Sé específico sobre lo que necesita ser corregido.

\--- task ---

Sugiere cambios y correcciones al LLM.

Por ejemplo:

"Esto es útil pero por favor incluye más frases motivacionales y adopta un tono más amistoso.
"Utiliza palabras menos complicadas y explica las cosas como si fuera un principiante".
"Sé más positivo y constructivo en tus comentarios".

\--- /task ---

### El paso más importante: La edición humana

\--- task ---

Revisa la respuesta una última vez para asegurarte de que sea fácil de seguir, correcta y completa.

**Depende completamente de ti (la persona) asegurarte de que la herramienta que estás utilizando funciona correctamente y de que su resultado no se utilice para hacer daño.**

\--- /task ---
