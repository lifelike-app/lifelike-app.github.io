# sitio_links — la página del botón del PDF

Se publica tal cual en **https://lifelike-app.github.io** (repo
`lifelike-app/lifelike-app.github.io`, organización gratis de GitHub).
Este folder es la fuente; el repo de la organización es sólo el destino.

- `l/index.html` — la página de "Bajar esta lista en LifeLike". Lee la lista
  del fragmento del link (`#…`, nunca llega a ningún servidor), la enseña y
  abre la app con `lifelike://lista#…`. Formato: `ListaCompartidaService`
  (`frontend/lib/services/lista_compartida_service.dart`).
- `index.html` — portada mínima de LifeLike.
- `.nojekyll` — para que GitHub Pages sirva carpetas con punto (la fase 2 va a
  necesitar `.well-known/apple-app-site-association` para los Universal Links).

**Los links ya impresos en PDFs apuntan aquí para siempre:** no mover
`l/` ni cambiar el formato del fragmento sin mantener la versión `v: 1`.

Para publicar un cambio: copiar estos archivos al repo de la organización y
hacer push a `main`.
