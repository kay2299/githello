# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines 
Underline 1
-----------
Underline 2
===========
# Formatos de enfasis
- formato *italika* de la primer forma
- formato _italika_ de la segunda forma
- formato **bold o strong** en la primer forma
- formato __bold o strong__ en la segunda forma
- formato ~~tachado~~ de la primer forma
- aqui podemos usar formato *italika* pero tambien **bold** y ~~tachado~~ *lol*

# Listas
1. Este es un item de una lista ordenada
2. Este es un item de una lista ordenada
3. Este es un item de una lista ordenada
- Este es un item de una lista desordenada
- Este es un item de una lista desordenada
- Este es un item de una lista desordenada

# Links
- <a href="http://www.google.com">Esto es un link HTML </a>
- [Esto es un link en Markdown](https://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Lol](https://img1.freepng.es/20190606/hjg/kisspng-github-computer-icons-font-awesome-bootstrap-logo-playmymusic-icon-free-of-papirus-apps-5cf89ad6437907.9920409515597964382764.jpg)

# Code Snippets
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
Codigo de JavaScript
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
-------- | -------- | ----------|
| Raymundo| Zertuche | 11244
| Raul | Perez | dnnj3j434

# Citas
esto es un gtexto referente a una cita que pondremos debajo:
> Esto es una cita

Esto no tiene nada que ver con la cita

> Esto es cita nueva

# Lineas Divisoras
Esto es un texto que sera dividido por guines medios.

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro texto dividido por guiones bajos.
___

# Saltos de linea
Esto es nuestro primero parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista
