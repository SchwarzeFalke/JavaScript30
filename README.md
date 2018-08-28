# JavaScript30
## Descripción general

Este repositorio sirve para el desarrollo de prácticas relacionadas
con el **_30 day vanilla JS coding challenge_**.

## Anotaciones

### Reto 01 - Drum Kit

Los atributos _data-*_ son empleados para almacenar información
personalizada de la página o aplicación. Los atributos _data-*_
nos brindan la abilidad de incrustar atributos de información
personalizada en todos los elementos HTML.

E.g.

```javascript
<div data-key="65" class="key">
```

El método querySelector() regresa el primer elemento que coincida
un/unos selector(es) especificado(s) en el documento.

E.g.

```javascript
const audio = document.querySelector(`audio[data-key="${e.keyCode}"]`);
const key = document.querySelector(`.key[data-key="${e.keyCode}"]`);
```
De tal manera que la variable _audio_ hará referencia al primer elemento
que coincida con algún atributo igual al código de tecla (así mismo, la
variable _key_)
