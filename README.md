# Proyecto Rick & Morty (pr06-lazy-components-andreuluis)

![Rick and Morty](https://rickandmortyapi.com/api/character/avatar/1.jpeg)

Este es un proyecto de Android nativo desarrollado con **Kotlin** y **Jetpack Compose** que muestra información sobre los personajes del universo de Rick y Morty. La aplicación utiliza componentes `Lazy` para mostrar listas de datos de manera eficiente y una arquitectura de navegación moderna.

##  Características

- **Interfaz moderna con Jetpack Compose:**  
  Toda la UI está construida de forma declarativa utilizando Jetpack Compose.
- **Navegación simple:**  
  Uso de `NavHost` de Navigation Compose para gestionar las pantallas.
- **Arquitectura MVVM:**  
  Separación clara de responsabilidades para mejorar la mantenibilidad.
- **Visualización eficiente de listas:**  
  Uso de `LazyColumn` y `LazyRow` para un rendimiento óptimo.
- **Diseño temático:**  
  Tema personalizado (`RickymortyTheme`) y fondo propio.

##  Estructura del Proyecto

- `app/src/main/java/com/example/rickymorty/`
  - `MainActivity.kt`: Punto de entrada y contenedor del `NavHost`.
  - `ui/theme/`: Tema, colores y tipografía.
  - `ui/views/`: Composables de las pantallas.
  - `viewmodels/`: ViewModels de la aplicación.
  - `data/`: Acceso a datos (repositorios, servicios, etc.).
- `app/src/main/res/`
  - Recursos como imágenes (`drawable`) y strings (`values`).
