# Guía rápida de markdown

Encontré un ejemplo espectacular en [The Markdown Guide](https://www.markdownguide.org)! y a partir de ello realicé esta guía resumida. Para que el documento se interprete como markdown, deben establecerle la extensión `.md`.

## Básico

Los elementos básicos son los encabezados, los efectos sobre los textos (negrita, itálica, etc), listas ordenadas o no ordenadas, bloques de código, línea horizontal, enlaces, e imágenes.

Para hacer párrafos, no hace falta iniciar la línea con algún carácter.

### Encabezados y tipos de fuente

# H1 encabezado de máximo tamaño
`# texto`
## H2 encabezado de tamaño medio
`## texto`
### H3 encabezado de tamaño pequeño
`### texto`

Si se desea, se puede continuar con el uso del # para hacer títulos de tamaño 4, 5 o 6.

### Efectos en fuente

**texto en negrita**
`** texto **`

*texto en cursiva*
`* texto *`

> texto en comillas 

`> texto`
Si se desean múltiples líneas con el efecto de las comillas, debemos iniciar cada línea adicional del párrafo con >.

### Listas
Para una lista ordenada, se indica al inicio de la línea el indice del número de elemento.

1. Primero
2. Segundo
3. Tercero
```
1. texto
2. texto 
3. texto
```

Lista no ordenada, se debe crear un elemento por línea iniciando con `- | + | *`

- Primero
- Segundo
- Tercero

### Código
Una sola línea de código, se indica con ``` `código` ```

Un bloque de código se inicia y finaliza con ` ``` `
```
Acá va nuestro bloque
...
y finaliza acá.
```

### Línea horizontal
Para hacer una línea del ancho de la página, se escribe al inicio de la línea ```---```

---

### Enlace
Para hacer un enlace, ponemos entre corchetes [] el texto del enlace, seguido de la dirección de refencia dentro de paréntesis.
[Texto del enlace](https://www.markdownguide.org)

``` [Texto del enlace](https://launion.com.gt)```

### Imagen
Para insertar una imagen, es muy similar a insertar un enlace, solo que en lugar de texto del enlace establecemos el texto alternativo (si no se logra cargar la imagen) y entre paréntesis la ruta de la imagen.
![logo](https://www.launion.com.gt/wp-content/uploads/2022/09/Logo-ILU-mas-imagen-zafra-54_Mesa-de-trabajo-1_010e00390_5611.jpg)

```
![texto alternativo]([https://launion.com.gt/logo.jpg)]
```

## Sintáxis extendida (avanzada)

Las siguientes son algunas avanzadas o combinaciones de las básicas.

### Tablas

```
| Sintaxis | Descripción |
| ----------- | ----------- |
| Encabezado | Título |
| Párrafo | Texto |
```

### Pie de página

Podemos añadir citas como a continuación [^1] ``` [^#] ```

[^1]: Esta es una cita de pie de página.

### Glosario

``` 
término 
: definición
```

### Tachado

```
~~texto a tachar~~
```

### Lista de tareas

```
- [x] Hacer la primera tarea
- [ ] Ahora la segunda
- [ ] Terminar el proyecto
```

### Emoji

Esto es genial! `:joy:` :joy:
