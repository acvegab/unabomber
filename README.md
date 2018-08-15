# Quick start

Para generar builds personalizadas en caso de que requieran lo primero hacer es tener instalado

Parcel utilizando Yarn or npm:

    yarn global add parcel-bundler

    npm install -g parcel-bundler

para levantar el entorno de desarrollo

    npm start

para generar un nuevo build

    npm build

esto va generar una carpeta build con los estaticos listos

    build
    ├── index.html
    ├── resources
    │   ├── cheetos-ui.json
    │   ├── cheetos-ui.png
    │   ├── shape.png
    │   └── ui
    │       ├── bg.jpg
    │       ├── brush-cheese.png
    │       ├── cheese-points.png
    │       ├── clock.png
    │       ├── hand-pointer.png
    │       ├── points-bar.png
    │       ├── time-bar-full.png
    │   └── time-bar.png
    └── src.hashXX.js

El juego expone 2 eventos y un metodo para configurar que son los siguientes

    app.on('gameLoaded', () => {
      
    });

    app.start(2);

    app.on('gameOver', ({ log, score }) => {
      
    });