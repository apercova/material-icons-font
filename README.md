# Actualización de fuente MaterialIcons-Regular desde [Google web fonts](https://fonts.googleapis.com/icon?family=Material+Icons).

Las instrucciones para de usar la fuente **MaterialIcons-Regular** para self-hosting se detallan en la documentación oficial de Material Icons en la sección [Setup Method 2. Self hosting](https://google.github.io/material-design-icons/)

Sin embargo, Google no ha actualizado las fuentes en su [repositorio](https://github.com/google/material-design-icons/tree/master/iconfont) con la última versión de la [fuente online](https://fonts.googleapis.com/icon?family=Material+Icons) 

A la fecha (2018-11-12), la versión de la fuente online es la _**v41**_.

En este repositorio se encuentran las fuentes actualizadas por version:

* MaterialIcons-Regular.eot
* MaterialIcons-Regular.svg
* MaterialIcons-Regular.ttf
* MaterialIcons-Regular.woff
* MaterialIcons-Regular.woff2

Las reglas CSS descritas en la documentación oficial son válidas a la fecha:

***
```css
@font-face {
  font-family: 'Material Icons';
  font-style: normal;
  font-weight: 400;
  src: url(https://example.com/MaterialIcons-Regular.eot); /* For IE6-8 */
  src: local('Material Icons'),
    local('MaterialIcons-Regular'),
    url(https://example.com/MaterialIcons-Regular.woff2) format('woff2'),
    url(https://example.com/MaterialIcons-Regular.woff) format('woff'),
    url(https://example.com/MaterialIcons-Regular.ttf) format('truetype');
}

.material-icons {
  font-family: 'Material Icons';
  font-weight: normal;
  font-style: normal;
  font-size: 24px;  /* Preferred icon size */
  display: inline-block;
  line-height: 1;
  text-transform: none;
  letter-spacing: normal;
  word-wrap: normal;
  white-space: nowrap;
  direction: ltr;

  /* Support for all WebKit browsers. */
  -webkit-font-smoothing: antialiased;
  /* Support for Safari and Chrome. */
  text-rendering: optimizeLegibility;

  /* Support for Firefox. */
  -moz-osx-font-smoothing: grayscale;

  /* Support for IE. */
  font-feature-settings: 'liga';
}
```


