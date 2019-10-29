
# hass-integration-edf_tempo
Custom component for [Home Assistant](https://home-assistant.io/)

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

## EDF Components
[![Version](https://img.shields.io/badge/version-0.0.1-green.svg?style=for-the-badge)](#) [![mantained](https://img.shields.io/maintenance/yes/2019.svg?style=for-the-badge)](#)

### Edf Tempo

Ce composant permet de récupérer les informations du site Tempo (edf), notamment dans l’optique de s’en servir (dans des scénarios) pour réduire ses consommations électriques en cas de fortes tensions sur le réseau électrique(selon les contrats d’électricité souscrits).

```yaml
sensor:
  - platform: edf_tempo
```
