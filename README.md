# Redirección de materialavicola.altermundi.net

La cartilla de alimentación agroecológica para la avicultura de la AFCI se mudó
a **https://materialavicola.cto.ar/**. Su código vive en
[`fabriciopetiso/cartilla_avicultura`](https://github.com/fabriciopetiso/cartilla_avicultura).

Este repositorio existe solo para que la dirección vieja siga funcionando: se
publica con GitHub Pages bajo el dominio `materialavicola.altermundi.net` y
manda cada visita a la misma página en la dirección nueva, conservando la ruta,
la consulta y el ancla. Por ejemplo:

- `materialavicola.altermundi.net/` → `materialavicola.cto.ar/`
- `materialavicola.altermundi.net/taller/` → `materialavicola.cto.ar/taller/`
- `materialavicola.altermundi.net/#cap4` → `materialavicola.cto.ar/#cap4`

`index.html` y `404.html` son el mismo archivo: GitHub Pages responde con
`404.html` cualquier ruta que no existe acá, y así también se redirigen las
subpáginas y los enlaces directos a las descargas.

El DNS de `materialavicola.altermundi.net` (un CNAME a `fabriciopetiso.github.io`)
lo administra AlterMundi y no hace falta tocarlo.
