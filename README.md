# Avance-del-proyecto-Espantap-jaros
# Proyecto de IoT con ESP32 y ThingSpeak

Este proyecto tiene como objetivo demostrar cómo utilizar un ESP32 para recopilar datos de un sensor de temperatura y humedad DHT22 y enviarlos a ThingSpeak para su posterior análisis y visualización. Además, se incluye un LED para indicar condiciones extremas de temperatura o humedad.

## Integrantes del Equipo
- Daniel Lorenzo Ramos
- Jeremy Andrew Rosillo
- Sebastian Fernando Castillo
- Jhonatan Bartolo
- Sebastian Alberto Rojas

## Contenido del Repositorio

- **Código:** El directorio `codigo/` contiene el código fuente del proyecto en C++ para el ESP32. Se utiliza la biblioteca DHTesp para interactuar con el sensor DHT22 y la biblioteca ThingSpeak para la comunicación con la plataforma ThingSpeak.

- **Esquemático:** El directorio `esquematico/` incluye un diagrama esquemático que muestra la conexión de los componentes en el proyecto. Se puede abrir en programas de diseño electrónico compatibles, como Fritzing o KiCad.

- **Imágenes:** El directorio `imagenes/` contiene imágenes referenciales del proyecto, que muestran la configuración de los componentes y el circuito en el simulador Wowki.

## Configuración y Uso

Para configurar y utilizar este proyecto, sigue estos pasos:

1. Clona este repositorio en tu máquina local.

2. Abre el código en el directorio `codigo/` en tu entorno de desarrollo Arduino o PlatformIO compatible con ESP32.

3. Realiza la conexión de los componentes según el diagrama esquemático en el directorio `esquematico/`.

4. Asegúrate de editar las variables `WIFI_NAME` y `WIFI_PASSWORD` en el código para que coincidan con tu red Wi-Fi.

5. Carga el código en tu ESP32 y observa la comunicación con ThingSpeak y el comportamiento del LED.

## Imágenes Referenciales

Aquí están las imágenes del proyecto:

- Resultados en la página web :
  <img src="https://i.imgur.com/XOc8xXi.png" alt="Esquemático" width="400"/>


- Circuito en Wowki :
  <img src="https://i.imgur.com/6yxJJoV.png" alt="Circuito en Wowki" width="400"/>

  
## Licencia

Este proyecto está bajo la Licencia MIT. Para obtener más información, consulta el archivo [LICENSE](LICENSE).

¡Esperamos que este proyecto te resulte útil y educativo!
