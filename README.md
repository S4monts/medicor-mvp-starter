Descripción del proyecto:
Creación y configuración de proyecto Node + Express con ESLint y Prettier. Servidor Local utilizando node.js de prueba para laboratorio.
Requisitos (Node, Git).
Instalar Node por la página oficial. Link: "https://nodejs.org/es/download"
Instalación: npm install .
Ejecución: npm run dev .
Ruta de prueba: /health .
Scripts útiles:
Para package.json
  "scripts": {
    "start": "node src/index.js",
    "dev": "nodemon src/index.js",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lint": "eslint .",
    "lint:fix": "eslint . --fix",
    "format": "prettier --write \"**/*.{js,json,md}\""
  }
  Scripts normalmente saldra vacio e impedira el funcionamiento del servidor, esto permite que funcione la ejecucion del servidor, reinicio al detectar cambios, revision de reglas y correción de estilos.
