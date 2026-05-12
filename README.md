### TP_IISAAI

**Se utilizó ChatGPT Plus (modelo GPT-5.5 Thinking)**

**Prompt utilizado**

Actuá como un Ingeniero de Software Senior especializado en UX Experimental y Frontend. El objetivo es desarrollar una prueba de concepto para la materia Ingeniería de Software asistida por IA (FIUBA) que explore los límites del Dark UX y el Hostile Design en un flujo de checkout web.

Genera un único archivo weird_checkout.html autocontenido que represente un formulario de pago deliberadamente diseñado para frustrar al usuario, cumpliendo estrictamente con lo siguiente:

1. Arquitectura y Estilo:

HTML5 Semántico: Estructura el checkout con <header>, <main>, <section> y <footer>.

Diseño Visual: Usa variables :root para una paleta "agresiva" de alto contraste que induzca fatiga visual.

Visualización de Producto: Muestra una imagen de un producto roto (fuente: http://googleusercontent.com/image_collection/image_retrieval/17331682067264360232_0) con el texto "Estado: Irreparable - Sin Garantía".

2. Mecánicas de Frustración Crítica (JS Moderno):

Validación Romana Estricta: El campo "Número de Tarjeta" solo acepta números romanos. Si detecta números arábigos (0-9), muestra un error indicando que el sistema solo soporta estándares de encriptación latinos clásicos.

Confirmación de CVV (Gaslighting): Al completar el tercer dígito del campo CVV, dispara automáticamente un alert o un banner persistente que diga: "Confirmado: El CVV ha sido correctamente leakeado".

El Calendario de la Eternidad: El vencimiento se elige mediante un calendario que inicia en Enero de 1980, sin selector de año, obligando al usuario a clickear mes a mes hasta el presente.

El Botón Fugitivo: El botón "Pagar" debe saltar a una posición aleatoria cada vez que el cursor se acerque a menos de 60px.

Reset de Inactividad: Si el usuario deja de escribir en cualquier input por más de 1.5 segundos, el campo se limpia automáticamente.

Checkboxes Excluyentes: Tres checkboxes obligatorios donde marcar uno desactiva inmediatamente los demás.

3. Calidad de Código:

Implementa todo con JS Moderno (ES6+), usando addEventListener, querySelector y funciones de flecha. El código debe ser una pieza de ingeniería impecable a pesar del propósito.

Añade comentarios irónicos en el código sobre la "seguridad" y "eficiencia" de estas trabas.

4. Restricciones de Salida:

Entrega únicamente el bloque de código del archivo index.html. Sin explicaciones adicionales.
