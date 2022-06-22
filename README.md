# Qatar WC 2022

_Sitio con información sobre la próxima copa del mundo y del país que la organiza, Qatar_

### Tecnoogías

- [HTML](https://developer.mozilla.org/es/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/es/docs/Web/CSS)
- [Sass](https://sass-lang.com/)
- [Bootstrap](https://getbootstrap.com/)

## Estructura del proyecto

```
.
├── css
├── js
├── resources
│   └── favicon
├── scss
│   ├── base
│   └── components
└── sections
```

### SEO

- Se agregaron meta para description y keywords titles para cada una de las páginas.

- Se optimizaron titles.

- Se agregó `target: _blank` a todas las referencias en el footer para el link externo que te lleva a la página oficial de la FIFA.

### Mixings

- Se incorporó un Mixing `playoff-style` para poder setear diferentes estilos de fuente y background en el fixture. El mismo se usa en los cuadros de octavos de final, cuartos, semifinal y final, este mixing recibe 2 parámetros, tamaño de fuente y background color.

### Extras

- nuevo `README.md`

- _for_ para generar los estilos de 8 clases de octavos de final.

- _each_ para generar los estilos de 4 clases para cuartos de final.

- _if_ para intercalar estilos entre pares e impares en octavos de final.

- Se incorpora `package.json` al repositorio.
