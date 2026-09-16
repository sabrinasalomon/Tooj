# Tooj — Guía de estilo

Estilo **minimalista en blanco, negro y gris**. Sin colores decorativos: el color no informa, informa la jerarquía.
Aplica al repositorio público, al diagrama de arquitectura y a los mockups.

## Colores

| Uso | Nombre | HEX |
|---|---|---|
| Principal | Negro | `#111111` |
| Secundario | Gris oscuro | `#555555` |
| Apoyo | Gris medio | `#767676` |
| Bordes | Gris claro | `#E0E0E0` |
| Líneas divisorias | Gris muy claro | `#EEEEEE` |
| Superficie | Gris de fondo | `#F2F2F2` |
| Fila resaltada | Gris tenue | `#F7F7F7` |
| Fondo | Casi blanco | `#FAFAFA` |
| Sobre fondo negro | Blanco y gris claro | `#FFFFFF` y `#BDBDBD` |

## Cómo se aplican

- **Fondo de pantalla:** casi blanco.
- **Barra superior y acción principal:** negro con texto blanco. En cada pantalla hay **una sola** acción en negro.
- **Acción secundaria:** gris oscuro con texto blanco, o contorno negro sobre blanco.
- **Tarjetas:** blanco con borde gris claro. Las que se quieren destacar llevan borde negro.
- **Texto:** negro para lo principal, gris medio para lo secundario.
- **Etiquetas de estado:** fondo negro cuando es urgente, gris medio cuando es aviso.
- **Nada de sombras ni degradados.** La jerarquía se logra con tamaño, peso y espacio.

## Tipografía

- Segoe UI, con Arial como respaldo. Es la tipografía estándar de Windows, así que los mockups se ven como se verá el sistema real.
- Títulos en negrita; textos de apoyo en tamaño menor y gris medio.
- Las cifras importantes (total, existencias, diferencias) van grandes: son lo que se lee de un vistazo.

## Reglas de las pantallas

- Pensadas para **teclado y escáner**, no para mouse. Las acciones frecuentes llevan tecla directa.
- Una acción principal por pantalla, bien visible.
- Textos en español, claros y sin términos técnicos.
- Mensajes de error que digan qué hacer, no solo qué falló.
- Estado de conexión siempre visible en la caja.
- Minimalista, pero nunca a costa de la claridad: si hace falta una palabra más para que se entienda, se pone.

## Identidad

- Nombre del producto: **Tooj**.
- **Portada del repositorio:** logotipo original en azul, archivo `img/logo.png`.
- **Dentro de las pantallas:** la marca aparece en blanco sobre la barra negra.
- En los mockups la marca va dibujada como **texto**, no como imagen insertada: un logotipo incrustado dentro de un SVG no se muestra cuando GitHub lo presenta en el README.
