GENERACIÓN DE MATERIALES EDUCATIVOS PERSONALIZADOS PARA EL APRENDIZAJE DE IDIOMAS MEDIANTE IA

1. Problemática a Resolver:
El aprendizaje de un idioma es un proceso complejo que varía considerablemente de un estudiante a otro, dependiendo de su nivel, estilo de aprendizaje y contexto cultural. Aunque existen recursos educativos para el aprendizaje de idiomas, muchos de ellos no están suficientemente adaptados a las necesidades individuales de los estudiantes. Este desafío se refleja en los siguientes problemas:
•Falta de personalización: Los estudiantes de idiomas tienen diferentes niveles de competencia (principiantes, intermedios, avanzados) y estilos de aprendizaje (visual, auditivo, kinestésico), lo que requiere enfoques adaptados a sus necesidades específicas.
•Generación de contenido visual y textual relevante: Es difícil crear materiales visuales como flashcards, diagramas o imágenes que complementen las lecciones y ayuden a los estudiantes a mejorar su comprensión.
•Escasez de recursos interactivos que hagan que el aprendizaje de idiomas sea dinámico, interesante y motivador.

2. Objetivo del Proyecto:
Desarrollar una solución basada en la generación automatizada de prompts utilizando IA para crear materiales educativos personalizados destinados al aprendizaje de un idioma, que se adapten tanto a las necesidades de los estudiantes como a sus estilos de aprendizaje.
Sub-objetivos:
1.Generación de contenido textual para:
oCrear ejercicios de vocabulario, gramática y comprensión lectora.
oGenerar diálogos y situaciones cotidianas adaptadas al nivel del estudiante.
oGenerar explicaciones de reglas gramaticales de manera personalizada.
2.Generación de contenido visual mediante IA para:
oCrear imágenes que complementen los conceptos gramaticales y vocabulario.
oDesarrollar flashcards visuales interactivas que ayuden a los estudiantes a memorizar palabras o frases.
oCrear mapas conceptuales y diagramas que visualicen la estructura del idioma.

3. Propuesta de Solución:
Generación de Prompts para el Aprendizaje de Idiomas
1.Modelo de IA Texto-Texto:
▪Ejercicios de vocabulario: Ejercicios de emparejar palabras con definiciones, completar frases o identificar palabras en un contexto.
▪Práctica de gramática: Ejercicios de conjugación, corrección de errores gramaticales o explicación de estructuras gramaticales.
▪Diálogos y situaciones: Generación de diálogos realistas para la práctica de conversación, que pueden estar adaptados a diferentes niveles de competencia.
▪Explicaciones gramaticales personalizadas: El modelo puede ofrecer explicaciones de reglas gramaticales adaptadas al nivel y estilo de aprendizaje del estudiante (por ejemplo, explicaciones más visuales o ejemplos prácticos).

2.Modelo de IA Texto-Imagen:
▪Flashcards visuales: Imágenes que representen palabras o frases clave, acompañadas de su traducción y ejemplo de uso en contexto.
▪Infografías: Diagramas visuales que expliquen reglas gramaticales, como la estructura de las oraciones, el uso de tiempos verbales o los pronombres.
▪Imágenes contextuales: Generar imágenes que ilustren situaciones cotidianas para el aprendizaje de vocabulario y frases (por ejemplo, "en el restaurante", "en la tienda").
▪Mapas conceptuales: Representaciones visuales que ayuden a los estudiantes a entender las conexiones entre diferentes conceptos del idioma (por ejemplo, diferentes tiempos verbales o categorías de vocabulario).

Cómo funcionará el sistema:
•El usuario ingresará un prompt inicial (por ejemplo, "Crear un ejercicio de vocabulario para un estudiante principiante sobre objetos en la casa").
•El modelo de IA generará contenido textual como listas de vocabulario, oraciones de ejemplo, y ejercicios.
•El modelo de IA también generará contenido visual complementario, como flashcards, imágenes de objetos de la casa o diagramas que representen la estructura del vocabulario.
•Los materiales generados se entregarán en formatos accesibles y editables, para que el docente o estudiante pueda adaptarlos según sus necesidades.

4. Justificación de la Viabilidad del Proyecto:
Viabilidad Técnica
La viabilidad técnica del proyecto se sustenta en el acceso a tecnologías avanzadas de procesamiento de lenguaje natural (PLN) y generación de imágenes mediante modelos de IA, que ya están disponibles y en constante mejora. Estos modelos son accesibles mediante APIs comerciales (como OpenAI y otras plataformas) que ofrecen facilidad de integración en sistemas educativos sin requerir una infraestructura tecnológica demasiado compleja.
Aspectos técnicos clave:
•Acceso a modelos de IA avanzados: Los modelos de IA como GPT-3 y DALL·E ya están en funcionamiento y pueden generar contenido textual y visual en tiempo real a partir de prompts personalizados.
Infraestructura accesible: Plataformas como OpenAI ofrecen APIs escalables, lo que permite integrar la generación automática de contenido en plataformas de aprendizaje existentes sin necesidad de desarrollar tecnología desde cero.
•Capacidad de adaptación: Estos modelos pueden ser entrenados o ajustados para generar materiales educativos específicos, lo que significa que pueden adaptarse a las necesidades y características de los estudiantes, independientemente de su nivel de competencia en el idioma.

5. Prompt inicial:
La aplicación se desarrollará en Python, utilizando herramientas como Visual Studio Code (VSC) para escribir y editar el código. Esta integrará funciones para interactuar con la API de OpenAI, lo que permitirá generar contenido creativo y didáctico para apoyar el aprendizaje del idioma inglés. Usando la API de OpenAI, los usuarios podrán acceder a diferentes tipos de contenido interactivo, como diálogos, ejercicios de escritura, corrección de textos y prácticas de vocabulario, todo adaptado al nivel de habilidad del usuario. Además, la API ayudará a ofrecer respuestas personalizadas, generando material de acuerdo a las necesidades específicas de cada usuario.
Para garantizar la eficiencia y el buen desempeño del código, se optimizará la aplicación utilizando Amazon CodeWhisperer, lo que permitirá mejorar el rendimiento y hacer ajustes automáticos que aseguren una experiencia fluida para el usuario.
El proyecto comenzará con un prompt inicial que dirá: 'Como experto en enseñanza del inglés, quiero que desarrollemos una aplicación en Python que permita a los usuarios generar contenido en inglés, así como también editar y mejorar los resultados obtenidos para ayudar en su aprendizaje del idioma.' La idea es que la aplicación no solo proporcione material educativo, sino que también permita a los usuarios interactuar activamente con el contenido y recibir retroalimentación en tiempo real.
En cuanto a la viabilidad económica, es fundamental tener en cuenta que el uso de la API de OpenAI conlleva costos. La API cobra según el volumen de uso y la cantidad de solicitudes realizadas, por lo que es importante planificar un presupuesto adecuado. Para reducir costos, se evaluará el uso eficiente de la API, priorizando las funcionalidades más relevantes y utilizando métodos para minimizar el número de consultas sin sacrificar la calidad del servicio. Con esta planificación, se asegurará que el proyecto siga siendo económicamente viable, a la vez que proporciona un valor educativo excepcional para los usuarios.

6. Requerimientos técnicos
Se crea una cuenta en Streamlit y además se conecta con la cuenta de GitHub
Se crea sesión en Amazon con la extensión para Vs CodeWhisperer
Además, se utiliza la herramienta ChatGPT para enriquecer el código que se requiera para la creación de la app
