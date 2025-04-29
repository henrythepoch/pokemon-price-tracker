<!-- README.md -->
# Pokémon TCG - Seguimiento de Precios (WebApp)

Esta es una aplicación web ligera para consultar precios de cartas de Pokémon TCG usando la API de [pokemontcg.io](https://pokemontcg.io/), incluyendo:

- Consulta por nombre de carta.
- Filtros por rareza y tipo.
- Seguimiento de precios (histórico local).
- Conversión automática de USD a MXN.
- Edición manual de tipo de cambio.
- Modo oscuro adaptativo.
- Funciona en cualquier navegador moderno o móvil (iPhone/Android).

## Características

- ⚡ GIF animado de carga con Pikachu electrificándose.
- 🔍 Búsqueda tolerante a errores y comodines.
- 🔼🔽 Indicadores de subida o bajada de precios desde la última consulta.
- 🧹 Botón para borrar todo el historial de seguimiento.
- 🌐 Compatible para despliegue en GitHub Pages, Netlify, Vercel.

## Uso Local

1. Descarga el archivo `index.html`.
2. Ábrelo en tu navegador favorito.
3. Opcionalmente, agrega como acceso directo en tu dispositivo móvil.

## Despliegue en GitHub Pages

1. Crea un nuevo repositorio en GitHub.
2. Sube el archivo `index.html`.
3. En la pestaña "Settings" → "Pages":
   - Source: `Deploy from a branch` → selecciona `main` y carpeta `/root`.
4. Espera unos minutos y accede al enlace generado: `https://<usuario>.github.io/<repositorio>/`

## Despliegue en Netlify

1. Ve a [Netlify](https://netlify.com) y crea una cuenta.
2. Haz drag & drop de tu archivo `index.html`.
3. Obtendrás un link público para compartir.

## Notas Técnicas

- Esta app utiliza la API gratuita de [pokemontcg.io](https://pokemontcg.io/) (requiere API Key).
- El tipo de cambio USD/MXN se consulta en tiempo real usando [exchangerate.host](https://exchangerate.host/).
- No requiere backend ni bases de datos externas.

## Licencia

MIT License © 2025

---

¡Disfruta tu seguimiento de cartas Pokémon de forma moderna y ligera! 🎴✨
