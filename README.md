# Cómo Hacer un Pwnagotchi 🐧

Este repositorio es una guía paso a paso para configurar tu propio Pwnagotchi, un dispositivo autónomo para aprender y practicar técnicas de redes WiFi de forma ética.

## ¿Qué es un Pwnagotchi?
Un Pwnagotchi es un dispositivo basado en inteligencia artificial que utiliza técnicas de redes WiFi para aprender y mejorar sus habilidades. Se ejecuta en dispositivos Raspberry Pi Zero W.

## Requisitos

### Hardware
- [ ] Raspberry Pi Zero W
- [ ] Pantalla E-Ink compatible (Waveshare 2.13inch E-Ink Display)
- [ ] Tarjeta MicroSD de al menos 16 GB
- [ ] Cable micro-USB
- [ ] Batería portátil

Consulta más detalles en la [documentación de hardware](./docs/hardware.md).

### Software
- Pwnagotchi OS (Descárgalo [aquí](https://pwnagotchi.ai))
- Etcher (para grabar la imagen en la SD)
- Acceso a una terminal o SSH

## Instalación

1. Descarga la imagen de Pwnagotchi desde el [sitio oficial](https://pwnagotchi.ai).
2. Usa Etcher para grabar la imagen en tu tarjeta MicroSD.
3. Configura el archivo `config.toml` para personalizar tu Pwnagotchi (más detalles [aquí](./docs/config.md)).
4. Conecta el Raspberry Pi, la pantalla E-Ink y la batería.
5. Arranca el dispositivo.

## Documentación

- [Configuración del Hardware](./docs/hardware.md)
- [Ajustes del Config.toml](./docs/config.md)
- [Solución de Problemas](./docs/troubleshooting.md)

## Contribuciones
¡Las contribuciones son bienvenidas! Si deseas contribuir, por favor abre un *issue* o envía un *pull request*.

## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](./LICENSE) para más detalles.
