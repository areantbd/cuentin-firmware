# Cuentín · firmware

Versiones publicadas del firmware de Cuentín para la placa Freenove FNK0104B.
La web de Cuentín lee `manifest.json` desde GitHub Pages y ofrece instalar la
última versión; cada `cuentin-<versión>.bin` es la imagen completa de la
aplicación, así que basta con instalar la última.

Se generan con `npm run publish-firmware` desde el proyecto de Cuentín. No
edites estos archivos a mano: la placa comprueba la versión y el SHA-256 del
manifiesto antes de activar una imagen.
