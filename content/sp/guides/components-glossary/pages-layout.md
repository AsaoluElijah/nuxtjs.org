---
title: 'The layout Property'
description: Cada archivo (primer nivel) en la carpeta `layouts` creará un layout personalizado accesible con la propiedad layout en el componente de página.
menu: Propiedad Layout
category: components-glossary
---

> Cada archivo (primer nivel) en la carpeta `layouts` creará un layout personalizado accesible con la propiedad layout en el componente de página.

- **Tipo:** `String` or `Function` (predeterminado: `'default'`)

Utilice la clave `layout` en sus componentes de página para definir a qué layout corresponde:

```js
export default {
  layout: 'blog',
  // OR
  layout(context) {
    return 'blog'
  }
}
```

