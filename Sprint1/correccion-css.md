# Corrección del bug de CSS

## Bug
El título del hero no se veía porque su color coincidía con el fondo.

## Cómo lo encontré
Abrí la página, inspeccioné el título con las herramientas de desarrollador
y revisé la regla CSS aplicada en la pestaña Styles.

## Solución
En `styles.css`, cambié el color de `.hero h1` de
`var(--color-bg)` a `var(--color-text)`.

## Comprobación
Recargué la página y comprobé que el título se ve y que el resto del diseño
sigue funcionando.