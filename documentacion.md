# proyecto-tienda-aurelion
# Gestión eficiente de inventario 


# Tema:
El proyecto se centra en la identificación de los productos con mayor y menor rotación en el inventario, con el propósito de optimizar la gestión del stock. Este análisis resulta fundamental para las empresas, ya que permite anticiparse a la demanda real, reducir pérdidas económicas y mejorar la eficiencia en la planificación de compras y abastecimiento.

# Problema:
La empresa puede estar comprando demasiado de algunos productos que casi no se venden y poco de los que más se venden.

# Solución:
La solución propuesta consiste en implementar un sistema de análisis de datos que permita:
- Identificar los productos más vendidos y los que permanecen estancados en el inventario.  
- Analizar la frecuencia de compra y las ciudades o regiones con mayor concentración de ventas.  
- Generar alertas y recomendaciones automáticas para reorganizar el inventario, optimizar las compras y reducir pérdidas económicas.


# Dataset de referencia:

# Fuente: 
La información utilizada para este análisis proviene de tablas en formato Excel que contienen datos estructurados sobre los productos, sus ventas y existencias en distintos periodos y ubicaciones. Estas tablas constituyen la base principal del estudio, ya que permiten observar y analizar el comportamiento de los productos dentro del inventario. A partir de ellas, es posible identificar patrones de venta, detectar cuáles artículos tienen una mayor rotación y cuáles permanecen en stock por más tiempo, lo que facilita la toma de decisiones estratégicas relacionadas con el control y la optimización del inventario.

# Definición: 
Este tipo de información corresponde a datos estructurados de origen primario, en este contexto, la gestión eficiente del inventario se entiende como el proceso de analizar los datos de ventas y existencias para determinar qué productos se comercializan con mayor frecuencia y cuáles tienden a mantenerse sin movimiento. El objetivo principal de esta gestión es optimizar el control del stock, prevenir pérdidas económicas y mejorar la planificación tanto de las compras como del abastecimiento. A través del análisis de estos datos, se busca obtener información valiosa que sirva para orientar decisiones estratégicas, como ajustar los pedidos de acuerdo con la demanda, la temporada o incluso la ubicación geográfica, asegurando así una administración más precisa y rentable del inventario.

# Estructura: 
Se adoptará un modelo de datos estructurados, caracterizado por su alto nivel de organización y formato predefinido. Estos datos se almacenarán entablas compuestas por filas y columnas.
   
# Tipos: 
Numéricos (enteros(INT) y decimales (FLOAT)), Texto (cadena de caracteres(STRING)) y Fecha (DATE).
   
# Escala: 
Nominal (Categórica) y De Razón (Ratio).

 
# Información: 
El programa desarrollado en Python presenta un menú interactivo en consola que permite al usuario explorar la información del proyecto de manera organizada.

Opciones del menú:

1 - Tema, problema y solución.
2 - Dataset de referencia.
3 - Información, pasos, pesudocódigo y diagrama del programa.
4 - Sugerencias y mejoras aplicadas con copilot.
5 - Salir.

# Pasos: 
1. El usuario ejecuta el programa en la terminal de Visual Studio Code.  
2. Se despliega el menú con las opciones numeradas.  
3. El usuario selecciona una opción ingresando el número correspondiente.  
4. El programa muestra la información asociada a la opción elegida.  
5. El menú se repite hasta que el usuario seleccione la opción de salida.

# Pseudocódigo:

// ------------------------------------------
// INICIO del Programa
// ------------------------------------------
INICIO

    // Mensaje de Bienvenida
    ESCRIBIR "Bienvenido al Proyecto del Grupo 6, por favor ingresa el número de opción que desees visualizar"
    
    // Inicialización para control del bucle
    opcion <- 0 
    
    // Bucle Principal: Repetir MIENTRAS la opción NO sea 5 (Salir)
    MIENTRAS (opcion != 5) HACER 
        
        // Mostrar Opciones
        ESCRIBIR "--- MENÚ ---"
        ESCRIBIR "1. Mensaje del Tema, Problema y Solución"
        ESCRIBIR "2. Mensaje del Dataset de Referencia"
        ESCRIBIR "3. Mensaje de Información, Pasos, Pseudocódigo y Diagrama"
        ESCRIBIR "4. Mensaje de Sugerencias y Mejoras aplicadas con Copilot"
        ESCRIBIR "5. Salir"
        ESCRIBIR "Ingrese su opción (1-5): "
        
        // Leer Opción
        LEER opcion 
        
        // Procesar Opción
        SEGÚN (opción) HACER
            
            CASO 1:
                ESCRIBIR "➡ ️ Ejecutando: Mensaje del Tema, Problema y Solución"
                
                
            CASO 2:
                ESCRIBIR "➡ ️ Ejecutando: Mensaje del Dataset de Referencia"
                
                
            CASO 3:
                ESCRIBIR "➡ ️ Ejecutando: Mensaje de Información, Pasos, Pseudocódigo y Diagrama"
                
                
            CASO 4:
                ESCRIBIR "➡ ️ Ejecutando: Mensaje de Sugerencias y Mejoras aplicadas con Copilot"
                
                
            CASO 5:
                ESCRIBIR "Gracias por haber visto nuestro proyecto, nos vemos en una próxima oportunidad..."
                // La acción de salida ocurre al finalizar el bucle
                
            DEFAULT:
                ESCRIBIR "OPCION FUERA DE RANGO, POR FAVOR INGRESA UNA OPCIÓN ENTRE 1 Y 5"
                
        FIN_SEGÚN
        
    FIN MIENTRAS
    
    ESCRIBIR "Saliendo del programa..."

FIN


# Diagrama del programa: (Ver imagen Diagrama de Flujo - Grupo 6.jpeg)


# Sugerencias y mejoras aplicadas con Copilot:
Le pedimos a Copilot sugerencias respecto a la documentación del proyecto, Copilot proporcionó la siguiente información:

Sugerencias de Mejora para la Documentación del Proyecto:

El siguiente documento presenta recomendaciones para enriquecer y estructurar de manera más clara la documentación del proyecto educativo sobre fundamentos de inteligencia artificial. Las sugerencias se enfocan en mejorar la redacción, la organización de ideas y la inclusión de apartados que aporten mayor valor académico y técnico.

1. Tema
Sugerencia Ampliar la redacción para que no solo se mencione el objetivo, sino también la relevancia del tema en el contexto empresarial.

Propuesta de redacción mejorada:
El proyecto se centra en la *identificación de los productos con mayor y menor rotación en el inventario*, con el propósito de optimizar la gestión del stock. Este análisis resulta fundamental para las empresas, ya que permite anticiparse a la demanda real, reducir pérdidas económicas y mejorar la eficiencia en la planificación de compras y abastecimiento.

Justificación: Una redacción más amplia aporta claridad sobre la importancia del tema y su impacto en la toma de decisiones estratégicas.

2. Problema
Sugerencia: Detallar las consecuencias del problema para la empresa.

Propuesta de redacción mejorada:
La empresa enfrenta un desequilibrio en la gestión de inventario: se adquieren en exceso productos con baja demanda, lo que genera acumulación y costos de almacenamiento, mientras que los artículos con alta rotación se compran en cantidades insuficientes, ocasionando desabastecimiento y pérdida de oportunidades de venta. Esta situación afecta directamente la rentabilidad y la satisfacción del cliente.

Justificación: Incluir las consecuencias hace que el problema se entienda en toda su magnitud.

3. Solución
Sugerencia: Incorporar un enfoque más estructurado en la descripción de la solución.

Propuesta de redacción mejorada:
La solución propuesta consiste en implementar un sistema de análisis de datos que permita:
- Identificar los productos más vendidos y los que permanecen estancados en el inventario.  
- Analizar la frecuencia de compra y las ciudades o regiones con mayor concentración de ventas.  
- Generar alertas y recomendaciones automáticas para reorganizar el inventario, optimizar las compras y reducir pérdidas económicas.  

Justificación: La organización en viñetas facilita la lectura y comprensión de la propuesta.

4. Dataset de Referencia
Sugerencia: Dividir la información en subapartados para mayor claridad.

Propuesta de redacción mejorada:
- Fuente: Tablas en formato Excel con registros internos de ventas y existencias.  
- Definición: Conjunto de datos estructurados que permiten observar el comportamiento de los productos en distintos periodos y ubicaciones.  
- Estructura: Tablas organizadas en filas y columnas, con un formato predefinido que facilita el análisis.  
- Tipos de datos:
  - Numéricos: enteros (INT) y decimales (FLOAT).  
  - Texto: cadenas de caracteres (STRING).  
  - Fecha: (DATE).  
- Escala de medición:
  - Nominal (categórica): categorías de productos, ciudades.  
  - De razón (ratio): cantidades vendidas, precios, niveles de stock.  

Justificación: La segmentación en apartados mejora la legibilidad y permite identificar rápidamente cada característica del dataset.

5. Estructura de Datos
Sugerencia: Ampliar la explicación para resaltar la importancia de la organización de los datos.

Propuesta de redacción mejorada:
Se adoptará un modelo de datos estructurados, caracterizado por su alto nivel de organización y formato predefinido. Este modelo facilita la aplicación de técnicas de análisis y garantiza la consistencia de la información, ya que los datos se almacenan en tablas compuestas por filas y columnas claramente definidas.

Justificación: Explicar el valor de la estructura de datos refuerza la base técnica del proyecto.

6. Programa Interactivo en Python
Sugerencia: Documentar el funcionamiento del menú paso a paso.

6.1. Descripción General
El programa desarrollado en Python presenta un *menú interactivo en consola* que permite al usuario explorar la información del proyecto de manera organizada.

6.2. Opciones del Menú
Se recomienda incluir las siguientes opciones en la documentación:

1. Presentación del Proyecto  
   Breve introducción al objetivo y alcance del trabajo.  

2. Tema y Problema  
   Resumen del tema central y la problemática identificada.  

3. Solución Propuesta  
   Descripción del enfoque de análisis de datos y beneficios esperados.  

4. Dataset de Referencia  
   Información sobre la fuente, estructura, tipos de datos y escalas.  

5. Resultados Esperados  
   Explicación de los beneficios de aplicar el análisis, como la optimización del inventario.  

6. Salir del Programa  
   Finaliza la ejecución del menú interactivo.  

6.3. Flujo de Uso
1. El usuario ejecuta el programa en la terminal de Visual Studio Code.  
2. Se despliega el menú con las opciones numeradas.  
3. El usuario selecciona una opción ingresando el número correspondiente.  
4. El programa muestra la información asociada a la opción elegida.  
5. El menú se repite hasta que el usuario seleccione la opción de salida.  

Justificación: Documentar el flujo de uso facilita la comprensión del programa y su aplicación práctica.

7. Recomendaciones Generales
- Utilizar un lenguaje claro y formal, evitando tecnicismos innecesarios.  
- Incluir tablas o diagramas que ilustren la estructura del dataset y el flujo del programa.  
- Añadir una sección de conclusiones que resuma los aprendizajes y beneficios del proyecto.  
- Incorporar ejemplos de ejecución del menú interactivo para reforzar la comprensión.  

Justificación: Estas recomendaciones fortalecen la presentación académica y técnica del proyecto.

8. Conclusión
La documentación debe reflejar tanto los aspectos teóricos (tema, problema, solución, dataset) como los técnicos (estructura de datos, programa interactivo, flujo de uso). Una redacción clara, organizada y detallada permitirá que el proyecto sea comprendido y replicado con facilidad en contextos educativos y profesionales.

# De todas las sugerencias proporcionadas, se decidieron aplicar estos puntos porque aportaban mayor claridad, coherencia con los objetivos del proyecto y valor técnico para su comprensión:
(1. Tema): Se eligió esta redacción porque sintetiza de forma precisa el propósito central del proyecto: analizar el comportamiento del inventario a partir de la identificación de productos con mayor y menor rotación, resalta la importancia empresarial del análisis de datos en la gestión del stock, además, el texto conecta claramente con los objetivos de optimización, predicción de la demanda y reducción de pérdidas, logrando un tono profesional y alineado con el campo de la inteligencia artificial aplicada a la toma de decisiones.
(3. Solución): Se eligió por su estructura ordenada, completa, específica y detalla qué hace el sistema y para qué sirve, los ejes aportan claridad al lector y comunica de manera sencilla cómo el análisis de datos puede transformar la gestión del inventario, combina un lenguaje accesible con una descripción técnica precisa, facilitando la comprensión del alcance y el impacto de la solución propuesta.
(6. Programa interactivo): Se eligió porque organiza de manera clara el funcionamiento del programa desarrollado en Python, describiendo su interacción con el usuario paso a paso, mantiene un equilibrio entre lenguaje técnico y accesible, ideal para el usuario, si bien se tuvo en cuenta la estructura porpuesta del menú, se mantuvieron las opciones del menú que ya se tenían establecidas para el programa de Phython.
