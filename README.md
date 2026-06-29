# BasuraCero MVD — Proof of Concept

🔗 **Demo en vivo:** https://TU-USUARIO.github.io/basura-cero-mvd-poc

Prototipo funcional desarrollado como validación de idea 
antes de la implementación en React + TypeScript.

## ¿Qué es?

Visualizador en tiempo real del estado de los **10.693 contenedores** 
de residuos domiciliarios de Montevideo, consumiendo datos directamente 
del Portal de Datos Abiertos de la Intendencia de Montevideo.

## Features

- 🗺️ Mapa interactivo con clustering dinámico por estado de recolección
- 📊 Dashboard con estadísticas en tiempo real por municipio
- 📍 Geolocalización — encontrá los contenedores más cercanos
- 🔍 Buscador de direcciones (Nominatim / OpenStreetMap)
- ♻️ Capa de contenedores de reciclaje seco
- 📱 Responsive

## Datos

Los datos se obtienen en tiempo real del Portal de Datos Abiertos 
de la Intendencia de Montevideo:

- [Estado de recolección de contenedores](https://ckan.montevideo.gub.uy/dataset/informacion-de-levantes-de-contenedores-domiciliarios)
- [Contenedores de reciclaje seco](https://ckan.montevideo.gub.uy/dataset/contenedores-para-clasificacion-de-residuos-secos-domiciliarios)

Licencia de datos: DAG-UY (Datos Abiertos Gubernamentales Uruguay)

## Stack

HTML · CSS · JavaScript · Leaflet · MarkerCluster · PapaParse · Nominatim

## Proyecto principal

La implementación completa en React + TypeScript + Node.js está en desarrollo.

---

*Iniciativa ciudadana independiente. No afiliada con la Intendencia de Montevideo.*
