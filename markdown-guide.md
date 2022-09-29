# Guía rápida de markdown

Encontré un ejemplo espectacular en [The Markdown Guide](https://www.markdownguide.org)! y a partir de ello realicé esta guía resumida.

## Básico

Los elementos básicos son los encabezados, los efectos sobre los textos (negrita, itálica, etc), listas ordenadas o no ordenadas, bloques de código, línea horizontal, enlaces, e imágenes.

### Encabezados y tipos de fuente

# H1 - # texto - encabezado de máximo tamaño
## H2 - ## texto - encabezado de tamaño mediano
### H3 - ### texto - encabezado de tamaño pequeño

### Efectos en fuente

**texto en negrita** - ** texto

*texto en cursiva* - * texto

> texto en comillas - > texto

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- First item
- Second item
- Third item

### Code

`code`

### Horizontal Rule

---

### Link

[Markdown Guide](https://www.markdownguide.org)

### Image

![alt text](https://www.markdownguide.org/assets/images/tux.png)

## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.

### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emoji

That is so funny! :joy:

(See also [Copying and Pasting Emoji](https://www.markdownguide.org/extended-syntax/#copying-and-pasting-emoji))

### Highlight

I need to highlight these ==very important words==.

### Subscript

H~2~O

### Superscript

X^2^
