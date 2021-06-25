# Versión actual: v1.2.2
# CABECERAS
# CABECERA H1
## CABECERA H2
### CABECERA H3
#### CABECERA H4
##### CABECERA H5 
###### CABECERA H6 

# Underlines
Underline 1
----------- 
Underline 2
===========
# Formatos de Emphasis

- letra *italica* de la primer forma.
- letra _italica_ de la segunda forma.
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
- Aquí podemos usar usar formato *italico* pero también **bold** y ~~tachado~~. 
# Listas

1. Esto es un  item de lista ordenada. 
2. Esto es un  item de lista ordenada.
3. Esto es un  item de lista ordenada.

- Esto es un lista desordenada
- Esto es una lista desordenada
- Esto es una lista desordenada
# LINKS 
- <a href="http://www.google.com">Esto es un enlace html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link](index.html)
# IMÁGENES
![Logo Github](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSASwXU2DKVVTo8rx0Jg-VpL3sh8xQk7gXAHA&usqp=CAU)

# CODE SNIPPETS
Código en Json
```JSON [
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]

```
``` JAVASCRIPT 
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;

```
# TABLAS
Name | Last name | Doc
-----|-----------|-----
Sofia | Fernandez | 54682554
Pepe | Hongo | 56454557
Debora |Tona |56421148
# CITAS
Esto es una referencia a una cita 
> Una cita es textual cuando se extraen fragmentos o ideas textuales de un texto. Las palabras o frases omitidas se reemplazan con puntos suspensivos (...). Para este tipo de cita es necesario incluir el apellido del autor, el año de la publicación y la página en la cual está el texto extraído.

Esto es otro texto
>Una cita es textual cuando se extraen fragmentos o ideas textuales de un texto. Las palabras o frases omitidas se reemplazan con puntos suspensivos (...). Para este tipo de cita es necesario incluir el apellido del autor, el año de la publicación y la página en la cual está el texto extraído.
# LINEAS DIVISORAS
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos

***

Esto es un texto dividido con guiones bajos

____
# SALTOS DE LÍNEA
Esto es un salto de línea.

Esto es otro párrafo. 

Esto es un tercer salto de línea.


