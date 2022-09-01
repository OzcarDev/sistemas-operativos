# Hola Mundo Markdown

Párrafo 1...

Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae, voluptatibus, molestiae omnis, voluptas ullam dolorem accusantium cumque minima quod saepe quis corporis eos nemo sequi dolore reiciendis dignissimos? Quis, provident.

Párrafo 3...

_cursiva_

**negrita**

**_cursiva y negrita_**

# Encabezado de nivel 1

## Encabezado de nivel 2

### Encabezado de nivel 3

#### Encabezado de nivel 4

##### Encabezado de nivel 5

###### Encabezado de nivel 6

[YouTube](https://youtube.com/jonmircha)

![This is JavaScript](https://jonmircha.com/img/blog/this-is-javascript.jpg)

---
Siguiente sección:

1. Primavera
1. Verano
1. Otoño
1. Invierno

- Primavera
- Verano
- Otoño
- Invierno

---

- Primavera
  - Abril
  - Mayo
  - Junio
- Verano
  - Julio
  - Agosto
  - Septiembre
- Otoño
  1. Octubre
  1. Noviembre
     - Día de Muertos
     - _Black Friday_
  1. Diciembre
- Invierno
  1. Enero
  1. Febrero
  1. Marzo
  
---   

> Todo lo que escuchamos es una opinión, no un hecho. Todo lo que vemos es una perspectiva, no la verdad. - Marco Aurelio.

> Todo lo que escuchamos es una opinión, no un hecho. Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio.

| Columna 1 | Columna 2 | Columna 3 |
| --------- | --------- | --------- |
| A         | B         | C         |
| D         | E         | F         |
| G         | H         | I         |

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```