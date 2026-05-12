**Prompt en Gemini (free)**
Dame un prompt para chatGPT Plus para que arme un checkout web siguiendo estos lineamientos:
Actúa como un Ingeniero de Software Senior experto en desarrollo Frontend y herramientas de IA. 
Necesito generar un proyecto para la materia Ingeniería de Software asistida por IA de la FIUBA.
Objetivo: Crear una "Interfaz de Usuario Frustrante" que sea funcional pero
molesta para el usuario.
Restricciones Técnicas:
Generá todo el código en un único archivo index.html.
Incluí el CSS dentro de etiquetas <style> y el JavaScript dentro de etiquetas <script>.
Usa HTML semántico (etiquetas main, section, header, footer).
En el CSS, definí variables en :root para la paleta de colores con colores agresivos.
Que los elementos de muevan y se frustren los clicks.
Funcionalidades:
Botón Huidizo: Un botón de "Enviar" que calcule una posición aleatoria y se mueva impidiendo que el usuario lo presione.
Formulario con Reset: Un campo de entrada de texto que, si el usuario deja de escribir por más de 2 segundos borre automáticamente todo el contenido.
Cursor Engañoso: Usa CSS para cambiar el cursor a un icono de "espera" (loading) permanentemente, aunque la página ya haya cargado.
Validación Infinita: Un checkbox de "No soy un robot" que, al ser marcado, desmarque automáticamente otros dos checkboxes obligatorios.
Output esperado: Solo el código del archivo index.html completo y funcional. No incluyas explicaciones externas, ya que el código debe hablar por sí mismo.
Comentarios: Con el prompt generado a partir de este hice un primer pedido a chatGPT

**Ajuste al pedido original sumando:**
Modificá el prompt para que para cargar el mes y año de la tarjeta haya que clickear en un calendario mensual que empiece en 1980
y sumá que el input de los los numeros de la tarjeta vayan en numeros romanos y de error si cargan numeros arabigos
Mantené el criterio de definir las mejores practicas de JS
Comentarios: Ajusté a mano el título "Numero de la tarjeta en números romanos"

**Prompt final utilizado en ChatGPT Plus (modelo GPT-5.5 Thinking)**

Actuá como un Ingeniero de Software Senior especializado en UX Experimental y Frontend. El objetivo es desarrollar una prueba de concepto para la materia Ingeniería de Software asistida por IA (FIUBA) que explore los límites del Dark UX y el Hostile Design en un flujo de checkout web.

Generá un único archivo index.html autocontenido que represente un formulario de pago deliberadamente diseñado para frustrar al usuario, cumpliendo estrictamente con lo siguiente:

1. Arquitectura y Estilo:

HTML5 Semántico: Estructura el checkout con <header>, <main>, <section> y <footer>.

Diseño Visual: Usa variables :root para una paleta "agresiva" de alto contraste que induzca fatiga visual.

Visualización de Producto: Muestra una imagen de un producto roto (fuente: http://googleusercontent.com/image_collection/image_retrieval/17331682067264360232_0) con el texto "Estado: Irreparable - Sin Garantía".

2. Mecánicas de Frustración Crítica (JS Moderno):

Validación Romana Estricta: El campo "Número de Tarjeta" solo acepta números romanos. Si detecta números arábigos (0-9), muestra un error indicando que el sistema solo soporta estándares de encriptación latinos clásicos.

Confirmación de CVV: Al completar el tercer dígito del campo CVV, dispara automáticamente un alert o un banner persistente que diga: "Confirmado: El CVV ha sido correctamente leakeado".

El Calendario de la Eternidad: El vencimiento se elige mediante un calendario que inicia en Enero de 1980, sin selector de año, obligando al usuario a clickear mes a mes hasta el presente.

El Botón Fugitivo: El botón "Pagar" debe saltar a una posición aleatoria cada vez que el cursor se acerque a menos de 60px.

Reset de Inactividad: Si el usuario deja de escribir en cualquier input por más de 1.5 segundos, el campo se limpia automáticamente.

Checkboxes Excluyentes: Tres checkboxes obligatorios donde marcar uno desactiva inmediatamente los demás.

3. Calidad de Código:

Implementá todo con JS Moderno (ES6+), usando addEventListener, querySelector y funciones de flecha. El código debe ser una pieza de ingeniería impecable a pesar del propósito.

Añadí comentarios irónicos en el código sobre la "seguridad" y "eficiencia" de estas trabas.

4. Restricciones de Salida:

Entregá únicamente el bloque de código del archivo index.html. Sin explicaciones adicionales.
