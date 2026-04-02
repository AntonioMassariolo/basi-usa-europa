# La rete delle basi militari USA in Europa

Mappa interattiva realizzata da Antonio Massariolo per Il Bo Live.

## Contenuto del repository

- `index.html` — mappa pronta da pubblicare
- `data/basi_usa_europa.geojson` — dataset geografico
- `data/basi_usa_europa.csv` — tabella pulita di supporto
- `.nojekyll` — utile per GitHub Pages

## Pubblicazione su GitHub Pages

1. Crea un nuovo repository su GitHub.
2. Carica tutti i file di questa cartella nella root del repository.
3. Vai in **Settings > Pages**.
4. In **Build and deployment**, scegli:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Salva e attendi la pubblicazione.

L'URL finale sarà simile a:

`https://NOMEUTENTE.github.io/NOME-REPOSITORY/`

## Embed

La mappa include un pulsante **Embed** nei credits. Una volta pubblicata, genera automaticamente il codice iframe.

Formato previsto:

```html
<iframe src="https://NOMEUTENTE.github.io/NOME-REPOSITORY/?embed=1" width="100%" height="720" style="border:0;" loading="lazy" allowfullscreen referrerpolicy="strict-origin-when-cross-origin"></iframe>
```

## Nota tecnica

La pagina usa librerie esterne caricate via CDN:
- Leaflet
- Leaflet.markercluster

## Crediti

Mappa realizzata da Antonio Massariolo per Il Bo Live.

Base dati: *Base Structure Report FY25* del Dipartimento della Difesa degli Stati Uniti.
