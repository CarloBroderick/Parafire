# Parafire — Visualizaciones / Visualizations

Visualizaciones HTML interactivas de los datos meteorológicos de Paraguay
(DMH-DINAC) para los modelos de incendios de INFONA. Abrí **`index.html`** para
el panel bilingüe; cada gráfico es un HTML independiente (Plotly via CDN /
Folium), por lo que pesan muy poco y se pueden abrir directamente.

*Interactive HTML visualizations of Paraguay's DMH-DINAC weather data for
INFONA's fire models. Open **`index.html`** for the bilingual dashboard; each
chart is a standalone HTML (Plotly via CDN / Folium), so files are tiny and can
be opened directly.*

## Contenido / Contents

### Mapas / Maps
- `mapa_estaciones_mch.html` — estaciones históricas MCH / historical MCH stations.
- `mapa_estaciones_emas.html` — estaciones automáticas EMAs / automatic EMAs stations.
- `mapa_combinado.html` — histórico vs. tiempo real (capas) / historical vs near-real-time (layers).

### Series temporales / Time series
- `cobertura_temporal_mch.html` — cobertura por estación-variable / per station-variable coverage.
- `dispersion_obs_emas.html` — dispersión de observaciones EMAs / EMAs observation spread.
- `serie_diaria_asuncion.html` — serie diaria Asunción / daily series, Asunción.
- `serie_mensual_asuncion.html` — serie mensual Asunción / monthly series, Asunción.

### Histogramas / Histograms
- `histograma_anios_fin_mch.html` — año de fin de registro / record end-year.
- `histograma_longitud_registro_mch.html` — longitud del registro / record length.
- `histograma_edad_lecturas_emas.html` — antigüedad de lecturas EMAs / EMAs reading age.

## Notas / Notes
- **Idioma / Language:** títulos en español (dominante) con subtítulo en inglés.
- **Datos / Data:** el archivo histórico MCH termina ~2022-07; las EMAs son
  actuales pero ~1/3 de las estaciones reenvían lecturas estancadas.
- Sin secretos en este folder. *No secrets in this folder.*

_Generado / Generated: 2026-06-16 12:31 PDT_
