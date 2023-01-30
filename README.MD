# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
--------------------------
Underline 2
==========================

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong**  de la primer forma.
- formato __bold o strong__  de la segunda forma.
- formato ~~tachado~~, forma normal.
- aqui podemos usr *formato italica*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es una item de lista ordenada.
2. Esto es una item de lista ordenada.
3. Esto es una item de lista ordenada.

- Esto es una item de lista desordenada.
- Esto es una item de lista desordenada.
- Esto es una item de lista desordenada.

# Links

- <a href="http://www.googlwe.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.googlwe.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

# Code Snippets

Codigo en JSON
```json
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

Codigo en JS
```js
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
| ------ | -------- | --------- |
| Tomas  | Tompson  | 345435353 |

# Citas
Esto es un texto referencte a una cita que ponemos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la anterior
> Esto es otra cita.

