# Proyecto Rick & Morty 

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

  <img width="350" height="782" alt="image" src="https://github.com/user-attachments/assets/031441cf-c01c-438f-ad48-4f186701a38f" />
<img width="356" height="778" alt="image" src="https://github.com/user-attachments/assets/7e3beea5-302c-4970-8b9e-12a0aacb8e25" />

