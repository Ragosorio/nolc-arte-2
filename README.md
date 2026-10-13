# nolc-arte-2

Segundo sitio de arte vectorial (SVG MAI) de **NO ONE LIKE CATS**, servido por GitHub Pages en
`https://ragosorio.github.io/nolc-arte-2/`. Es el **mismo origen** que el juego (`https://ragosorio.github.io/no-one-like-cats/`), así que no hay CORS y las partidas no se tocan.

- `nolc-arte` (sitio 0) sigue sirviendo **todo** el arte publicado hasta la Parte II, con las mismas rutas.
- Aquí (sitio 1) va solo el arte **nuevo** (Parte III en adelante). Lo decide `game/src/art/artShardPins.ts` en el repo del juego.

Igual que el primero, el arte **no** se guarda en este repo: el workflow `publish.yml` lo toma del repo del juego
(variables: `NOLC_ART_TIERS=full`, `NOLC_ART_SHARD=1`, `NOLC_ART_COUNT=2`). Solo SVG, nunca scripts ni raster.

**Orden de activación:** `docs/part-iii/12-hosting-arte-p3.md` en Ragosorio/no-one-like-cats.
