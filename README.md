

# Practicas css y html basicos


## Practicas css y html basicos

# ¿Qué es CSS?
- CSS son las siglas de Cascading Style Sheets
- CSS describe cómo se mostrarán los elementos HTML en la pantalla, el papel o en - otros medios.
-CSS ahorra mucho trabajo. Puede controlar el diseño de varias páginas web a la vez
- Las hojas de estilo externas se almacenan en archivos CSS

## CSS Syntax
![image text](https://www.w3schools.com/css/img_selector.gif)

- **Selector** : un selector es una etiqueta HTML en la que se aplicará un estilo. Puede ser cualquier etiqueta como h1 o table, etc.
- **Propiedad** : una propiedad es un tipo de atributo de etiqueta HTML. En pocas palabras, todos los atributos HTML se convierten en propiedades CSS. Pueden ser de color , borde , etc.
- **Valor** : los valores se asignan a las propiedades. Por ejemplo, la propiedad de color puede tener un valor rojo o # F1F1F1, etc.
- Puede poner la sintaxis de la regla de estilo CSS de la siguiente manera:

Ejemplo explicado
- **p** es un selector en CSS (apunta al elemento HTML que desea aplicar estilo: <p>).
- **colores** una propiedad y redes el valor de la propiedad
- **text-alignes** una propiedad y centeres el valor de la propiedad

### El selector universal de CSS
- El selector universal (*) selecciona todos los elementos HTML de la página.
Ejemplo : Ver Ejercicio4 

### El selector de agrupación CSS
- Será mejor agrupar los selectores para minimizar el código.
Para agrupar selectores, separe cada selector con una coma.
Ejemplo: Ver Ejercicio4

**Son distintas forma de que todo los elementos tenga el mismo color ccs.**

## selector { property: value }
| Selector | Example | Example description |
| --- | --- | --- |
| #id  | #firstname  | Selects the element with id="firstname"  |
| .class  | .intro  | Selects all elements with class="intro"  |
| element.class | p.intro  | Selects only <p> elements with class="intro"  |
| * | *  |Selects all elements  |
| element | p | Selects all <p> elements  |
| element,element,.. | div, p  | Selects all <div> elements and all <p> elements  |

# CSS: Texto
- Color del texto: color  [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Colortexto.html).
- Color de fondo: background-color [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Colordefondo.html).
- Alineación horizontal: text-align [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Alineacionhorizontal.html).
- Sangría: text-indent [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Sangria.html).
- Espaciado de letras: letter-spacing [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Espaciadoletras.html).
- Espaciado de palabras: word-spacing  [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Espaciadopalabras.html).
- Decoración: text-decoration [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Decoracion.html).
- Mayúsculas / minúsculas: text-transform [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCSS/Texto/Mayusculasminusculas.html).

----------------------------------------------------------------------------


- clasePseudoClases: **Pseudo classes:** Define el estilo de un estado especial de un elemento. **Pseudo elementos:** Define el estilo de una parte específica de un elemento. [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/clasePseudoClases).

- claseModeloCaja. Modelo de caja **CONTENT, PADDING, BORDER, MARGIN,** [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseModeloCaja).

- claseHerencia: (por ejemplo, color o font-size) son heredadas. Esto significa que si no se les asigna ningún valor específico, lo heredarán del que tenga el elemento padre en la jerarquía HTML.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseHerencia).

- claseEspecificidad: La **especificidad** es la manera mediante la cual los navegadores deciden qué valores de una propiedad CSS son más relevantes para un elemento y, por lo tanto, serán aplicados.
[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseEspecificidad).


- claseCombinadores :Nos permiten combinar múltiples selectores y crear una mayor especificidad [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCombinadores).

![image text](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseCombinadores/Combinadores.png)

- claseMedidas: Las unidades **absolutas** son un tipo de medida fija que no cambia. Las **unidades relativas** son un tipo de medida mucho más potente y habitual en el CSS que creamos generalmente. Al contrario que las unidades absolutas, las **unidades relativas** dependen de algún otro factor (resolución, tamaño de letra, etc...).
[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseMedidas).

![image text](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseMedidas/Medidas.png).

- clasePosition:  Esta propiedad tiene un montón de posibles valores, sus nombres no tienen sentido y son casi imposibles de memorizar. **static " Por defecto",absolute,relative,fixed,sticky** [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/clasePosition).


- claseDisplay [GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/blob/css/css/claseDisplay).


----------------------------------------------------------------------------




# Responsive Design

### Mobile First / Only
**Mostly Fluid:** El patrón Mostly fluid consiste, principalmente, en una cuadrícula fluida. Por lo general, en las pantallas grandes o medianas se mantiene el mismo tamaño y simplemente se ajustan los márgenes en las más anchas.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/responsivedesign/mostlyFluid).

**Column drop:** En el caso de los diseños con varias columnas de ancho completo, durante el proceso de colocación de columnas éstas únicamente se colocan de forma vertical debido a que el ancho de la ventana es demasiado reducido para el contenido.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/responsivedesign/columnDrop).

**Layout shifter:** El patrón Layout shifter es el más adaptable, ya que posee varios puntos de interrupción en diferentes anchos de pantalla.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/responsivedesign/layoutShifter).


**Off canvas:** En lugar de apilar contenido verticalmente, el patrón Off canvas coloca contenido menos usado (tal vez menús de navegación o de apps) fuera de la pantalla y solo lo muestra cuando el tamaño de la pantalla es suficientemente grande.


### Recomendación
Separa siempre tus archivos de CSS por break point
- mobile.css / style.css
- tablet.css
- desktop.css

### Responsive Imágenes
Para trabajar con imagenes responsivas se recomienda usar la "etiqueta picture".[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/responsivedesign/ResponsiveImgs).
----------------------------------------------------------------------------



# Accesibilidad

### Semántica

La semántica está relacionada con las etiquetas contenedoras en HTML5, por ejemplo: header, main, sidebar y footer. Estas agregan información importante para aquellos que tengan problemas con la visualización de la página. Les permite a estos usuarios orientarse en qué sección de la página se encuentran.
Por eso, es importante utilizar las diferentes etiquetas que HTML5 ofrece para tener la mejor semántica posible y la accesibilidad.

### Textos
Respecto a los textos en mejor usar medidas relativas, como "rem", en lugar de medidas absolutas. Esto mejora la accesibilidad visual.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/accesibilidad/texto).

### Labels, alt y titles
- El uso de <label> en los formularios facilita la interacción de las personas y software con ellos. Por ejemplo al apretar la barra de espacio en un input que despligue un submenú, este se mostrará.
- alt en las imágenes proporciona una descripción para un lector de contenido.
- El atributo title puede ser usado en las etiquetas img y a para dar una descripción de sus contenidos al hacer hover.[GitHub Pages](https://github.com/Jesus-Angel-VS/mis_practicas_web/tree/css/accesibilidad/claseLabelAltTitle).

