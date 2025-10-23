Le pedimos a Copilot sugerencias respecto a la documentación del proyecto usando el motor de IA GPT-5 con el siguiete Prompt:

/fix @workspace 
Contexto:
Estoy trabajando en un proyecto educativo sobre fundamentos de inteligencia artificial en Visual Studio Code. 
El proyecto incluye un programa en Python que muestra un menú interactivo con opciones para visualizar información del proyecto. 
La documentación debe cubrir todos los aspectos teóricos y técnicos del trabajo.

Objetivo:
Genera sugerencias para mejorar la documentación del proyecto
Quiero que propongas sugerencias claras, precisas y bien redactadas para las secciones de la documentación que creas conveniente mejorar, esta es la documentación:
- Tema: Identificar qué productos se venden más y cuáles se quedan estancados para mejorar la gestión del stock.
- Problema: La empresa puede estar comprando demasiado de algunos productos que casi no se venden y poco de los que más se venden.
- Solución: Analizar los datos para encontrar los productos más y menos vendidos, su frecuencia o ciudad donde más se compran, y generar alertas o recomendaciones para organizar el inventario y evitar pérdidas.
- Dataset de referencia (fuente, definición, estructura, tipo y escala): La información utilizada para este análisis proviene de tablas en formato Excel que contienen datos estructurados sobre los productos, sus ventas y existencias en distintos periodos y ubicaciones. Estas tablas constituyen la base principal del estudio, ya que permiten observar y analizar el comportamiento de los productos dentro del inventario. A partir de ellas, es posible identificar patrones de venta, detectar cuáles artículos tienen una mayor rotación y cuáles permanecen en stock por más tiempo, lo que facilita la toma de decisiones estratégicas relacionadas con el control y la optimización del inventario. Este tipo de información corresponde a datos estructurados de origen primario. En este contexto, la gestión eficiente del inventario se entiende como el proceso de analizar los datos de ventas y existencias para determinar qué productos se comercializan con mayor frecuencia y cuáles tienden a mantenerse sin movimiento. El objetivo principal de esta gestión es optimizar el control del stock, prevenir pérdidas económicas y mejorar la planificación tanto de las compras como del abastecimiento. A través del análisis de estos datos, se busca información valiosa que sirva para orientar decisiones estratégicas, como ajustar los pedidos de acuerdo con la demanda, la temporada o incluso obtener la ubicación geográfica, asegurando así una administración más precisa y rentable del inventario.
- Estructura: Se adoptará un modelo de datos estructurados, caracterizado por su alto nivel de organización y formato predefinido. Estos datos se almacenarán entablas compuestas por filas y columnas.
- Tipos: Numéricos (enteros(INT) y decimales (FLOAT)), Texto (cadena de caracteres(STRING)) y Fecha (DATE).
- Escala: Nominal (Categórica) y De Razón (Ratio).

Tambien quiero que generes la información y pasos para el programa interactivo


Formato:
Devuelve las sugerencias organizadas en formato Markdown (.md) en donde las describas y expliques por qué las sugieres, usa un lenguaje formal y un tono adecuado para una presentación académica o técnica.

Restricciones:
No modifiques la idea principal del proyecto.
Solo da recomendaciones de redacción, estructura y contenido.
Usa un lenguaje claro y profesional, sin tecnicismos innecesarios.
