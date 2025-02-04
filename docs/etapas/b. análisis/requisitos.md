# 💾 REQUISITOS 
## REQUISITOS MUSICSTATS

- La aplicacion debe permitir al usuario introducir sus datos de spotify en el sistema
- La aplicación procesará todos los datos introducidos
- La aplicación tendrá un menú en el que se podrá elegir entre varias opciones: Resumen general, Filtrar datos (año, mes, día), Ver
  primera vez que se escuchó una cancíon/artista, ver datos de una canción/album/artista.
- En el resumen general se verá un top 10 canciones más escuchadas por el usuario, top 10 artistas más escuchados y top 10 albumes
  más escuchados. También se verá el total de escuchas, el total de minutos y los años que comprenden los datos recogidos.
- En la opción de ver datos de una canción/albúm/artista se podrán ver datos como el número total de escuchas y el tiempo total de escucha, además de ver la primera y última vez que se reprodujo.
- Desde cada canción se podrá acceder a la propia app de spotify con su url.
- La aplicación debe ser rápida, fácil de usar, y se podrá utilizar en cualquier buscador.

(Para posibles futuras actualizaciones)

- Ver gráficos con información sobre las estadísticas.

## ESTRUCTURA DE LOS DATOS (Campo / Contenido)

- ts -> Marca de tiempo en UTC que indica cuando se dejó de reproducir una canción (AAAA-MM-DDTHH:MM:SSZ)
- username -> Nombre de usuario de spotify.
- platform -> Plataforma que se uso al escuchar la canción.
- ms_played -> milisegundos que duró la reproducción
- conn_country -> cod.pais para la reproducción
- ip_addr_decrpyted -> IP registrada en la reproducción
- user_agent_decrypted -> Agente donde se reprodujo la canción
- master_metadata_track_name -> Nombre de la pista
- master_metadata_album_artist_name -> Nombre del artista o podcast.
- master_metadata_album_album_name -> Nombre del album
- spotify_track_uri -> uri de spotify de la reproducción
- episode_name -> Nombre de episodio del podcast
- episode_show_name -> NOmbre de programa
- spotify_episode_uri -> Uri del podcast
- reason_start -> Razón por la que se empezó la reproducción
- reason_end -> Razón por la que se dejó de reproducir
- shuffle -> Se usó modo aleatorio (true/false)
- skipped -> Se saltó la canción
- offline -> Se escuchó en el modo sin conexión (true/false)
- offline_timestamp -> Marca de tiempo de cuando se usó el modo sin conexión
- incognito_mode -> Indica si la canción se escuchó en una sesión privada (null/true/false)
