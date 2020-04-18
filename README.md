Las cabeceras son tipografias para el titulo del documento:


# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

Underline se usa como alternativa a las anteriores cabeceras:

Underline1
-----------
Underline
==========

El enfasis es utilizado do para enfatizar en palabras o conceptos clave:

- formato *italica* primera forma.
- formato _italica_ segunda forma.
- formato **bold / strong** primer forma.
- formato __bold /strong__ segunda forma.
- formato ~~tachado~~.
- *todos* _los_ **formatos** __pueden__ ~~usarse en una sola linea~~. 

Las listas son usadas para ordenas elementos de forma ordenada o no ordenada:

1. Esto es un Item de lista ordenada.
2. Esto es un Item de lista ordenada.
3. Esto es un Item de lista ordenada.
- Esto es un Item de lista desordenada.
- Esto es un Item de lista desordenada.
- Esto es un Item de lista desordenada.

Los links son enlaces redireccionables a una dirección local/web establecida>

- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http>//google.com)
- [Esto es un link al index](index.html)

Agregar ilustraciones también es posible con Markdown:

![Logo Github](https://www.muylinux.com/wp-content/uploads/2017/06/github.png)

Es posible incluir codigo no ejecutable desde Markadown, esto son es llamado Code Snippets:

Código en Python
``` python
@requires_authorization
def somefunc(param1='', param2=0):
    r'''A docstring'''
    if param1 > param2: # interesting
        print 'Gre\'ater'
    return (param2 - param1 + 1 + 0b10l) or None

class SomeClass:
    pass

>>> message = '''interpreter
... prompt'''
````

Código en Javascript
``` Javascript
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
