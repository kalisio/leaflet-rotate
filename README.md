# leaflet-rotate

A Leaflet plugin that allows to add rotation functionality to map.

Forked from [Raruto/leaflet-rotate](https://github.com/Raruto/leaflet-rotate) with additional fix/features that have been integrated:
* new `touchRotateInertia` option to start rotating only when exceeding this thershold (see discussion in https://github.com/Raruto/leaflet-rotate/pull/48),
* fix for floating layers while rotating/zooming the map (see discussion in https://github.com/Raruto/leaflet-rotate/pull/61),
* new `offset` option for the `setBearing` method to allow off-centered rotation in screen-space pixels.
