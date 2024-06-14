
# REACT-NATIVE-APP

Este es el repositorio del proyecto `REACT-NATIVE-APP`, una aplicación desarrollada con React Native y Expo. El proyecto utiliza JavaScript y JSX para la creación de interfaces, y el estado global se maneja con Context API. La aplicación se conecta a un backend proporcionado por Appwrite.

## Instalación

Para instalar y ejecutar este proyecto en tu máquina local, sigue los siguientes pasos:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/react-native-js.git
   cd react-native-js
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia la aplicación:
   ```bash
    npx expo start -c
   ```
4. Matar el proceso
   ```bash
    lsof -i :8081
   ```

## Uso de Context para el Estado Global

El estado global de la aplicación se maneja utilizando Context API. El archivo principal de configuración de contexto es `GlobalProvider.js` dentro de la carpeta `context`.

## Conexión con el Backend

La aplicación se conecta a un backend utilizando Appwrite. El endpoint configurado para la conexión es:

```
endpoint: "https://cloud.appwrite.io/v1"
```

Asegúrate de configurar tus credenciales y otros parámetros necesarios para la autenticación y uso de los servicios de Appwrite.

## Componentes

La aplicación cuenta con varios componentes reutilizables, ubicados en la carpeta `components`. Aquí hay una breve descripción de algunos de ellos:

- `CustomButton.jsx`: Botón personalizado con estilos y funcionalidad adicionales.
- `EmptyState.jsx`: Componente para mostrar un estado vacío cuando no hay datos.
- `FormField.jsx`: Componente para campos de formulario reutilizables.
- `InfoBox.jsx`: Caja de información para mostrar detalles importantes.
- `SearchInput.jsx`: Barra de búsqueda.
- `Trending.jsx`: Componente para mostrar tendencias.
- `VideoCard.jsx`: Componente para mostrar tarjetas de video.

## Recursos

Los recursos como fuentes, íconos e imágenes se encuentran en la carpeta `assets`.

## Constantes

Las constantes para íconos e imágenes están definidas en la carpeta `constants`.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:

```
REACT-NATIVE-APP
├── .expo
├── .vscode
├── app
│   ├── auth
│   ├── tabs
│   ├── search
│   ├── _layout.jsx
│   └── index.jsx
├── assets
│   ├── fonts
│   ├── icons
│   ├── images
│       ├── adaptive-icon.png
│       ├── favicon.png
│       ├── icon.png
│       └── splash.png
├── components
│   ├── CustomButton.jsx
│   ├── EmptyState.jsx
│   ├── FormField.jsx
│   ├── index.js
│   ├── InfoBox.jsx
│   ├── SearchInput.jsx
│   ├── Trending.jsx
│   └── VideoCard.jsx
├── constants
│   ├── icons.js
│   ├── images.js
│   └── index.js
├── context
│   └── GlobalProvider.js
└── lib
```

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.
