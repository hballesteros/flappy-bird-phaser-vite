# Flpappy Bird

Flpappy Bird es un juego simple inspirado en el clásico Flappy Bird, desarrollado con Phaser 3. El objetivo es controlar un pájaro que debe evitar colisionar con tuberías mientras vuela a través de un paisaje.

## Características

- Gravedad aplicada al pájaro.
- Control del pájaro mediante clics del ratón o la tecla de espacio.
- Tuberías estáticas para pruebas iniciales.
- Reinicio automático de la posición del pájaro cuando sale de la pantalla.

## Estado del Proyecto

Este proyecto está actualmente en desarrollo. Las características básicas están implementadas, pero aún se están realizando mejoras y nuevas funcionalidades.

## Requisitos

- [Node.js](https://nodejs.org/) (versión 12 o superior)
- [npm](https://www.npmjs.com/) o [yarn](https://yarnpkg.com/)

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu-usuario/flpappy-bird.git
   cd flpappy-bird
   ```
2. Instala las dependencias del proyecto:
   ```bash
   npm install
   # o si usas yarn
   yarn install
   ```
3. Inicia el servidor de desarrollo:
   ```bash
   npm start
   # o si usas yarn
   yarn start
   ```
4. Abre tu navegador en http://localhost:8080 para jugar.

## Instrucciones de Juego

- Haz clic en la pantalla o presiona la tecla `Espacio` para hacer que el pájaro aletee y suba.
- El pájaro caerá debido a la gravedad.
- El juego se reiniciará automáticamente si el pájaro sale de la pantalla por arriba o por abajo.

## Estructura del Proyecto

- `src/`: Contiene el código fuente del juego.
  - `index.js`: Archivo principal donde se configura y ejecuta el juego.
- `assets/`: Carpeta que contiene las imágenes utilizadas en el juego.

## Futuras Mejoras

- Implementación de tuberías móviles.
- Contador de puntuación.
- Pantalla de inicio y reinicio.
- Mejora de los gráficos y animaciones.

## Contribuciones

Las contribuciones son bienvenidas. Si deseas contribuir, por favor, abre un *issue* o un *pull request* en el repositorio.

## Licencia

Este proyecto está licenciado bajo la [Licencia MIT](./LICENSE).
