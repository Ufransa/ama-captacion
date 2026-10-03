# AMA · Plan de captación en Gran Canaria

Plan de captación de clientes y posicionamiento en buscadores para AMA, pyme de construcción
con base en **Vecindario (Santa Lucía de Tirajana)** y trabajo en toda Gran Canaria. Tres
líneas en el plan: pintura, fontanería con contra incendios y trabajos en altura. La soldadura
sigue en el negocio, pero llega por cartera y queda fuera del plan.

Una sola página HTML, sin dependencias salvo la fuente Archivo de Google Fonts.

## Cómo verlo

- **En local:** abrir `index.html` en el navegador.
- **En la tele:** botón «Presentar en pantalla grande», o añadir `#presentar` a la dirección.
  Se avanza con las flechas del teclado o del mando, deslizando el dedo o con los botones.
  Esc para salir. Los controles se ocultan solos a los tres segundos.

## Publicarlo en GitHub Pages

1. Crear un repositorio (en kebab-case, por ejemplo `ama-captacion`).
2. Subir esta carpeta.
3. `Settings` → `Pages` → `Source: Deploy from a branch` → rama `main`, carpeta `/ (root)`.
4. Queda en `https://<usuario>.github.io/ama-captacion/`.

Al llamarse `index.html` no hace falta configurar nada más.

## Qué hay dentro

Dieciséis apartados: portada (con lo que cambió el 3 de octubre), quién compra, precios,
por qué hay trabajo, competencia real, estudio de mercado de contra incendios, plan en 90 días,
dos guías interactivas (ficha de Google desde cero y anuncios de Google, con el reparto de
300 €), cambiar de línea, calculadora de rentabilidad, presupuesto, IGIC y subvenciones, redes,
indicadores, lo que no haríamos y fuentes.

## Dos avisos sobre el contenido

- **Los datos caducan.** La competencia de Google Maps, las ayudas y las ordenanzas se
  comprobaron el 14 de septiembre de 2026; pintura, contra incendios y Google Ads, el 3 de
  octubre de 2026. Conviene repasarlos cada trimestre.
- **Dos regímenes distintos de inspección de edificios.** En Las Palmas de Gran Canaria la
  ordenanza municipal obliga a inspección técnica de fachadas desde los diez años de
  antigüedad, repetida cada diez. En los municipios sin ordenanza propia rige la Ley 4/2017
  del Suelo de Canarias: 80 años, con eficacia de veinte. **En Santa Lucía de Tirajana no se
  ha encontrado ordenanza propia publicada**, así que ahí no sirve el argumento de los diez
  años. Confirmarlo en el ayuntamiento (928 72 72 00) antes de usarlo con un administrador.
  Lo que sí vale en cualquier municipio son las órdenes de ejecución por seguridad,
  salubridad y ornato.

## Verificación

Comprobado con Playwright y Chromium a 390×844, 1440×900 y 1920×1080, con y sin modo
presentación: sin desbordamiento horizontal, sin errores de consola, contraste WCAG AA
en el texto renderizado, foco visible y animaciones desactivadas con `prefers-reduced-motion`.
No usa `localStorage` ni `sessionStorage`.
