# Requisitos de Hardware para Pwnagotchi

Para construir tu Pwnagotchi, necesitarás algunos componentes específicos que permitirán que el sistema funcione correctamente.

## 1. Raspberry Pi Zero W

- **Descripción**: Este es el "cerebro" del Pwnagotchi. El Raspberry Pi Zero W es el modelo preferido debido a su tamaño reducido, bajo consumo de energía y conectividad Wi-Fi integrada.
- **Alternativas**: Aunque es posible usar otros modelos de Raspberry Pi (como el Pi 3B+ o 4), el Pi Zero W es el recomendado por la comunidad debido a su portabilidad y facilidad de uso.

## 2. Pantalla E-Ink (Waveshare 2.13inch)

- **Descripción**: Una pantalla de tinta electrónica (E-Ink) es esencial para mostrar información del estado de tu Pwnagotchi.
- **Modelo recomendado**: Waveshare 2.13 inch e-Paper Display HAT.
  - **Conectividad**: Conecta la pantalla al GPIO del Raspberry Pi Zero W.
  - **Resolución**: 212 x 104 píxeles.
- **Alternativas**: Cualquier pantalla E-Ink compatible con Raspberry Pi podría funcionar, pero la Waveshare es la más comúnmente utilizada y soportada por Pwnagotchi.

## 3. Tarjeta MicroSD (16GB o más)

- **Descripción**: El sistema operativo Pwnagotchi se ejecuta desde una tarjeta MicroSD. Se recomienda un tamaño de al menos 16 GB para asegurarte de que tengas suficiente espacio para los datos capturados y configuraciones.
- **Recomendación**: Utiliza tarjetas de alta velocidad para un mejor rendimiento (clase 10 o superior).

## 4. Batería Portátil (Power Bank)

- **Descripción**: Tu Pwnagotchi necesitará una fuente de alimentación portátil para funcionar de manera autónoma.
- **Requisitos**:
  - **Capacidad**: 5000 mAh o más (según cuánto tiempo quieras que funcione).
  - **Voltaje**: 5V con al menos 1A de salida.
- **Alternativa**: También puedes usar una batería LiPo con un controlador de carga USB, pero es más avanzado.

## 5. Cable Micro-USB

- **Descripción**: Se necesita un cable micro-USB para conectar la batería portátil al Raspberry Pi Zero W y alimentarlo. Asegúrate de que el cable pueda manejar suficiente corriente.

## 6. Opcional: Antena Wi-Fi Externa (para mayor alcance)

- **Descripción**: Aunque el Raspberry Pi Zero W tiene Wi-Fi integrado, algunos usuarios prefieren añadir una antena Wi-Fi USB externa para mejorar el alcance de la red y la potencia de la señal.
- **Modelos recomendados**: Alfa AWUS036NHA, TP-Link TL-WN722N v1.
- **Requisitos**: Debe ser compatible con el modo "monitor".

---

### **docs/config.md**

```markdown
# Configuración del Archivo `config.toml` de Pwnagotchi

El archivo `config.toml` es donde puedes personalizar el comportamiento de tu Pwnagotchi. Aquí te mostramos los ajustes más importantes y cómo configurarlos correctamente.

## 1. Nombre del Pwnagotchi

```toml
name = "pwnagotchi"
