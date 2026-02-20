# 🎓PROYECTO LIMPIEZA DE DATOS EN EXCEL🎓

Pequeño proyecto orientado a la revisión del proceso de limpieza y preparación de datos de un dataset en formato CSV. Para ello, se ha utilizado un dataset "sucio" con el find e dificultar la tarea y ayudar al aprendizaje.

El dataset contiene información de ventas minoristas con las siguientes variables principales:
- Transaction ID 
- Customer ID 
- Category Item 
- Payment Method 
- Location 
- Discount Applied 
- Quantity 
- Price Per Unit 
- Total Spent Transaction 
- Date

Una vez redistribuidos los datos en una tabla dinámica, encontré los siguientes errores:
1) Textos inconsistentes con espacios, mayúsculaes y minúsculas.
2) Cantidades negativas o ceros.
3) Números con formato texto.
4) Valores faltantes.
5) Cálculos totales que no coincidian.
6) Fechas adjudicadas a formatos erroneos.

Para solucionarlo, he utilizado los siguientes procesos:
1) Eliminación de espacios sobrantes función: ESPACIOS () y normalización de las letras con la función NOMPROPIO ().
2) Tratamiento de valores erroneos en las columnas Quantity ≤ 0 y Price ≤ 0. Ambos transformados en espacios vacíos.
3) Conversión de texto numérico con la función VALOR () y evasión de errores con la función SI.ERROR ().
4) Recalcular el ingreso total (Quantity * Price Per Unit) y gestionar las operaciones inconsistentes.
5) Por último, gestión de las fechas inválidad y cambiar su formato a fecha corta.

Aunque no se deba hacer, he querido mantener todo el proceso realizado como evolución del proyecto con el fin, de poder observar el proceso realizado. Por ello, las columnas auxiliare sos ecundarias que deberían de haber sido eliminadas al final, las he mantenido.

En resumen, el proyecto tenía como objetivo depurar y preparar el dataset para su posterior análisis. 

Por último, solo me queda darte las gracias por leer hasta aquí. 

Un saludo. 

GPx-E
