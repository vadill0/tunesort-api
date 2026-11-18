# Alcance del proyecto

## Objetivo
Aplicación web full-stack (MERN) que importa las canciones favoritas de un usuario
de Spotify y las agrupa automáticamente en playlists por género, coherentes y de
tamaño equilibrado, además de permitir puntuar canciones y álbumes.

## MVP
- Login con Spotify (OAuth 2.0 con PKCE)
- Importar canciones favoritas, con caché para artistas y géneros en MongoDB
- Generar playlists por género con un algoritmo de agrupación
- Puntuar canciones
- Despliegue en Render + MongoDB Atlas

## Deseable
- Puntuación de albumes (en base a sus canciones)
- Exportar playlists a Spotify
- Parámetros de agrupación ajustables
- Gráficas de géneros

## Fuera de alcance
- Uso público multiusuario (Spotify limita los usuarios en modo desarrollo a 5)
- App móvil, reproducción y recomendaciones

## Restricciones
- Stack MERN, dos repositorios (api y web)
- Cuenta de Spotify premium para la app en modo desarrollo

