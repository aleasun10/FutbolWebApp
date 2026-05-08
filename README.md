# FutbolWebApp

Proyecto web móvil desarrollado en DataFlex 2025 conectado a una base de datos MySQL llamada `futbol`.

## Descripción

Esta aplicación permite consultar información relacionada con una base de datos de fútbol. El proyecto incluye las vistas solicitadas para las tablas principales y un Dashboard con tarjetas de acceso.

## Tecnologías utilizadas

- DataFlex 2025 Studio
- MySQL
- MySQL Workbench
- ODBC
- Git y GitHub

## Tablas utilizadas

Las tablas principales usadas en la aplicación son:

- `liga`
- `equipo`
- `posicion`
- `entrenador`
- `jugador`

## Funcionalidades implementadas

- Creación del workspace `FutbolWebApp`.
- Creación del proyecto web móvil en DataFlex.
- Conexión con la base de datos MySQL `futbol`.
- Importación de las tablas MySQL al proyecto DataFlex.
- Creación de Data Dictionaries para las tablas principales.
- Creación de vistas Select y Zoom para:
  - ligas
  - equipos
  - posiciones
  - entrenadores
  - jugadores
- Dashboard principal con tarjetas de acceso a cada listado.
- Visualización de relaciones entre tablas usando nombres legibles:
  - Equipo -> Liga
  - Entrenador -> Equipo
  - Jugador -> Equipo

## Vistas creadas

- `SelectLiga.wo`
- `ZoomLiga.wo`
- `SelectEquipo.wo`
- `ZoomEquipo.wo`
- `SelectPosicion.wo`
- `ZoomPosicion.wo`
- `SelectEntrenador.wo`
- `ZoomEntrenador.wo`
- `SelectJugador.wo`
- `ZoomJugador.wo`
- `Dashboard.wo`

## Base de datos

La base de datos se llama `futbol` y fue creada en MySQL a partir del script proporcionado por DataFlex

## Autor

Alejandro Muñoz Paredes
