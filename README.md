# Sensores remotos: espectro electromagnético, plataformas y drones

Presentación interactiva de 38 diapositivas (HTML5, CSS y JavaScript puros, sin librerías externas) que resume una revisión sobre percepción remota: el espectro electromagnético, las ventanas atmosféricas, las firmas espectrales, los sensores pasivos y activos, las plataformas (suelo, aire, espacio), los drones y misiones de NASA y ESA (Landsat, ECOSTRESS, GEDI, NISAR y BIOMASS).

**Autor:** Jesus Enrique Flores Riera ([@jf-floresriera](https://github.com/jf-floresriera))

## Cómo verla

Abre `index.html` en cualquier navegador moderno. Todo está en ese único archivo.

| Acción | Control |
| --- | --- |
| Avanzar / retroceder | Flechas, barra espaciadora, rueda del ratón, deslizar en pantallas táctiles o los botones inferiores |
| Primera / última | `Inicio` / `Fin` |
| Pantalla completa | `F` o el botón ⛶ |
| Ir a una diapositiva | Añade `#número` a la URL, por ejemplo `index.html#18` |

Para publicarla como página web, activa **GitHub Pages** en *Settings → Pages* con la rama `main` y la carpeta raíz.

## Contenido

- **Fundamentos (1–9):** percepción remota, espectro, albedo, ventanas atmosféricas, firmas espectrales y regiones útiles. Incluye dos diapositivas con figuras reales de NASA y NOAA.
- **Regiones del espectro (10–14):** ultravioleta, visible, infrarrojo cercano, SWIR, térmico y microondas.
- **Sensores y plataformas (15–21):** pasivos y activos, plataformas, órbitas, resoluciones (con figuras reales de NASA), satélites meteorológicos y radar SAR.
- **Aplicación propia: guía SAR multisensor (22–23):** comparador interactivo entre radar (Sentinel-1 banda C y ALOS-2 banda L) e imagen óptica Sentinel-2 en el Meta, Colombia, y la retrodispersión por banda. Viene de [SAR-and-Optical-Multisensor-Interpretation-Guide](https://github.com/jf-floresriera/SAR-and-Optical-Multisensor-Interpretation-Guide).
- **LiDAR y drones (24–28):** GEDI, sensores a bordo, costos y limitaciones.
- **Aplicación propia: fenotipado con dron (29–31):** timelapse interactivo de cinco vuelos, calibración con Sentinel-2, grilla de parcelas, dinámica del dosel y heredabilidad. Viene de [pea_drone](https://github.com/jf-floresriera/pea_drone).
- **Misiones (32–35):** Landsat 8 y 9, ECOSTRESS, NISAR y BIOMASS, con un resumen.
- **Referencias y cierre (36–38).**

Las figuras de los repositorios propios están incrustadas en `index.html`. Las de NASA y NOAA se cargan desde sus sitios, así que necesitan conexión a internet. Si no cargan, se muestra una tarjeta con el enlace a la fuente.

Cada diapositiva enlaza sus fuentes en la parte inferior, y las dos diapositivas de referencias enlazan las 44 fuentes.

## Notas

- Las curvas de transmisión atmosférica, firmas espectrales y absorción SWIR son esquemas ilustrativos, no datos medidos.
- Antes de exponer, confirma el estado operativo de cada misión en las páginas de NASA y ESA.
- Los límites del SWIR varían entre autores (1,100–3,000 nm según NASA Earth Observatory; 1,000–2,500 nm según ITRC).
