# Restaurant Conchita · Sitio web y menú digital

Propuesta de página web y menú digital para **Restaurant Conchita**, en Cd. Lerdo, Durango.
Powered by **SSS.SOLUTIONS**.

## Páginas

| Archivo | Qué es |
| --- | --- |
| `index.html` | Página principal: portada, favoritos, historia de la casona, mapa y horario |
| `menu.html` | Menú digital con buscador, categorías y ficha de cada platillo |
| `propuesta.html` | Propuesta para presentarle al restaurante |

Son archivos HTML sin dependencias: se abren con doble clic en cualquier navegador.

## Cómo editar el menú

En `menu.html`, busca el bloque `EDITA AQUÍ EL MENÚ`. Cada platillo se escribe así:

```js
{n:"Chilaquiles rojos o verdes", d:"Con crema, queso y cebolla.", p:110, img:"chilaquiles", t:["fav"]},
```

- `n` nombre · `d` descripción · `p` precio en pesos
- `img` nombre de la foto en `img/` (sin `.jpg`)
- `t` etiquetas: `"fav"` favorito, `"veg"` vegetariano, `"pic"` picante

## Cómo poner las fotos reales

Guarda las fotos en `img/` con los nombres de `img/LEEME.txt` (por ejemplo `fachada.jpg`).
Reemplazan solas a las fotos de prueba. Antes de publicar el sitio de verdad, cambia todas
las fotos de prueba (Wikimedia Commons) por fotos del restaurante.

## Horario

El letrero de abierto/cerrado usa la hora de Lerdo, de 8:00 a 16:00, y marca cerrado
el Viernes Santo, el 25 de diciembre y el 1 de enero.

## Publicar con GitHub Pages

Settings → Pages → Branch `main` → Save. Las páginas quedan en
`https://<usuario>.github.io/CONCHITA-RESTAURANTE-/`.
