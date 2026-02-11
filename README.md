# Amiibo Vault

Una aplicación Android educativa que implementa el patrón **Offline-First** para mostrar una colección de figuras Amiibo.

## Descripción

Aplicación Android construida con Jetpack Compose, MVVM y Clean Architecture que consume la Amiibo API para mostrar una lista de amiibos con:

-> Búsqueda en tiempo real

-> Paginación (scroll infinito)

-> Pull to refresh

-> Caché local con Room + Flow

-> Consumo de API con Retrofit

-> Manejo de errores de red

La app usa StateFlow para observar cambios en la base de datos y actualizar la UI automáticamente cuando los datos cambian, manteniendo una experiencia fluida incluso sin conexión.

## Video

https://youtu.be/J1jHgFAAb9U