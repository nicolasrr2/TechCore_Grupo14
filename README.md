# TecnoCore - Aplicación de E-Commerce para Android

Proyecto final para la Evaluación Parcial 2. 
TecnoCore es una aplicación móvil Android nativa que simula una tienda de productos tecnológicos, implementando una arquitectura moderna 

## Autores
- NICOLAS ROMO
- JESUS GARCIA
- GitHub:https://github.com/nicolasrr2/TechCore_Grupo14
- Trello:https://trello.com/b/tEJGE9iU/proyecto-tecnocore

## Características Implementadas
- **Persistencia Local con Room:** Toda la información (usuarios, productos, carrito) se guarda en una base de datos local SQLite gestionada por Room, usando coroutines y Flow para un rendimiento asíncrono y reactivo.
- **Autenticación de Usuarios:** Flujo completo de registro e inicio de sesión.
- **Catálogo de Productos:** La pantalla principal muestra una lista de productos obtenidos de la base de datos.
- **Carrito de Compras:** Funcionalidad para añadir productos a un carrito persistente.
- **Uso de Recursos Nativos:**
  - **Cámara:** El usuario puede tomar una foto de perfil durante el registro.
  - **Ubicación:** Se puede obtener la última ubicación conocida del dispositivo desde la pantalla principal.
- **Animaciones y Feedback Visual:** Transiciones suaves entre pantallas y notificaciones al interactuar con la aplicación.
- **Gestión de Permisos:** Solicitud de permisos en tiempo de ejecución para la cámara y la ubicación.

## Requerimientos Técnicos
- **Lenguaje:** Kotlin
- **UI:** Android XML 
- **Versión Mínima de Android:** API 24 (Nougat)
- **Librerías Principales:** ViewModel, LiveData, Room, Coroutines, ViewBinding, Material Components, Google Play Services Location.
