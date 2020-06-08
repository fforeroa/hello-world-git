#Version de curso
Version actual : v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6


# Underlines
Underline1
----------

Underline2
==========


# Formato de emphasis
- formato letra *italica* de la primer forma.
- formato letra _italica_ de la segunda forma.
- formato **bold o strong**  de la primer forma.
- formato __bold o strong__  de la primer forma.
- formato ~~tachado~~ , formato normal
-aqui podemos usar *italica* pero tambien 
**bold** y  ~~tachado~~.

#Listas
1. Es un item de lista ordenada. 
2. Es un item de lista ordenada. 
3. Es un item de lista ordenada.

-Es un item de lista desordenada.
-Es unitem de lista desordenada.
-Es un item de lista desordenada.

#Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link Markdown](http://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo GITHUB](https://www.trecebits.com/wp-content/uploads/2019/11/GITHUB.jpg)

# Code Snipets
Codigo en JSON
```JSON
[
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

Codigo e Javascript
```Javascript
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

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
|Maxi    |Burgos    | 3223233   |
|Tomas   |Tompson   | 3223233   |

# Citas
Esto es un texto referente a una cita :
>Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior
>Esto es otra cita

#Lineas divisoras
Esto es un texto que será dividido por guiones medios

---

Esto es otro texto dividido por asteriscos

***

Este es otro texto divido por guiones bajos

___


#Saltos en linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
-Lista

