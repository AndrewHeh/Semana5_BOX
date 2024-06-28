# BOX MODEL

- basicamente es el modelo de una caja representado de forma rectangular / cuadrada, este contiene contenido, padding,borde y margen. uno sobre otro

```html

 <div class="box"></div>

```

## SELECTOR UNIVERSAL

- se representa con una comilla "*". De forma automática, este selecciona todos los elementos en un documento.

```css
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}
```

## Que es el box-sizing: border-box? : 
se refiere a que el tamano de la caja se va a mantener estable

### Diferencias entre Margin y Padding

- Margin : Espacio fuera del borde del elemento. Separa el elemento de los demás.

- Padding : Espacio dentro del borde del elemento. Separa el contenido del borde.

### Márgenes Negativos
- Permiten mover el elemento en la dirección opuesta del margen aplicado.

### Colapsado de Márgenes
- Los márgenes verticales adyacentes ya sea superior e inferior se combinan en uno solo, tomando el mayor de los dos valores