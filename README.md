# Kodeeksempel på brug af WMS matrikelkort fra Datafordeleren

Kodeeksemplet er baseret på kortbiblioteket [OpenLayers](https://openlayers.org/)

## Installation

* Installer npm/node fra [Node.js](https://nodejs.org/en/)
* Klon dafkort repositoriet
* Installer matrikelwms afhængigheder: npm ci
* Din tjenestebrugers username og password indsættes som queryparameter i WMS tjenestens URL. Linje 31 i index.js.

Test lokalt: npm start

Build: npm run build