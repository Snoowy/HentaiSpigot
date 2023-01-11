[website]: https://exylcraft.com
[discord]: https://discord.gg/exylcraft

<img src="https://i.kym-cdn.com/photos/images/original/001/431/488/a4f.jpg" alt="petal_logo" width="80" height="80">

# Hentai spigot Performance Minecraft JAR

Hentai spigot is a performance-oriented fork of Purpur intended to increase performance for entity-heavy servers by implementing multi-threaded and asynchronous improvements.


Hentai spigot focuses on two specific improvements for entity-heavy servers:

- **Async Pathfinding** Entity pathfinding is offloaded to asynchronous threads to significantly reduce processing from the main thread
- **Multi-threaded Entity Tracking** Entity tracking can take advantage of multiple threads to greatly reduce dependence on main thread processing


As Hentai spigot is forked from Purpur, it enjoys several performance features from other projects including:

- **Sentry Integration** Easily track all errors coming from your server in excruciating detail (Pufferfish)
- **Better Entity Performance** Reduces the performance impact of entities by skipping useless work and making barely-noticeable changes to behavior (Pufferfish)
- **Partial Asynchronous Processing** Partially offloads some heavy work to other threads where possible without sacrificing stability (Pufferfish)
- **8x Faster Map Rendering** Reduces or eliminates lag spikes caused by plugins like ImageOnMap or ImageMaps (Pufferfish)
- **30% faster hoppers** over Paper (Airplane)
- **Reduced GC times & frequency** from removing useless allocations, which also improves CPU performance (Airplane)
- **Fast raytracing** which improves performance of any entity which utilizes line of sight, mainly Villagers (Airplane)
- **Built-in profiler** which has 0 performance hit and easy to read metrics for both server owners and developers (Airplane)



## License

Hentai spigot is licensed under GPLv3.
