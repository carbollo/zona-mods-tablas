# Zona Mods · Tablas de Cheat Engine

Recopilación de **1.719 tablas de Cheat Engine (`.CT`) para juegos single-player en Windows**, preparada como fuente automática del servidor de trainers de Zona Mods.

Solo están las tablas que el importador de Zona Mods convierte en al menos un cheat que la app puede ejecutar. Las que solo traen scripts que todavía no soporta se han dejado fuera. Cada archivo es una **copia sin modificar** del original.

## Cómo usarlo en Zona Mods

El servidor coge como mucho 200 archivos por fuente, así que las tablas van repartidas en 9 lotes. En el panel (**Fuentes automáticas**) añade una fuente por lote:

```
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-01
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-02
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-03
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-04
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-05
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-06
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-07
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-08
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-09
```

Conviene añadirlas con **Publicar** desactivado y revisar lo importado antes de publicarlo.

## Estructura

```
lote-NN/
  <autor>__<repositorio>/
    ORIGEN.md        enlace al original y licencia
    LICENSE          la del autor, si la tiene
    *.CT             sus tablas
INDICE.md            todas las tablas: juego, proceso, cheats utilizables y enlace al original
```

## Qué se ha dejado fuera

- **Juegos online o con servidor**: GTA V / FiveM, Halo MCC, Counter-Strike, StarCraft II, Warcraft III, Joint Operations, Battlefield, Call of Duty, Forza Horizon, Left 4 Dead y Lethal Company. Zona Mods es solo para partidas offline y se niega a conectarse si detecta un anticheat.
- Tablas duplicadas (mismo contenido en varios repositorios).
- Archivos de más de 8 MB, que el servidor no descarga.

## Autores y licencias

Todo el mérito es de sus autores. Este repositorio solo reúne y filtra su trabajo; las tablas siguen bajo las condiciones de cada original. Las que tienen licencia (MIT, GPL, AGPL, BSD, ISC) la conservan en su carpeta.

**¿Eres autor de alguna de estas tablas y prefieres que no esté aquí?** Abre una *issue* y la retiro sin más.

| Origen | Forja | Licencia | Tablas |
|---|---|---|---|
| [ragnaroks/CheatTables](https://github.com/ragnaroks/CheatTables) | GitHub | AGPL-3.0 | 124 |
| [bbfox0703/Mydev-Cheat-Engine-Tables](https://github.com/bbfox0703/Mydev-Cheat-Engine-Tables) | GitHub | GPL-3.0 | 149 |
| [eArmada8/kiseki_ce](https://github.com/eArmada8/kiseki_ce) | GitHub | GPL-3.0 | 38 |
| [Sora3100/Tales_of_Cheat_Tables](https://github.com/Sora3100/Tales_of_Cheat_Tables) | GitHub | GPL-3.0 | 22 |
| [jisopo/CheatEngineTables](https://github.com/jisopo/CheatEngineTables) | GitHub | GPL-2.0 | 45 |
| [SeulYoung/TrainerCollection](https://github.com/SeulYoung/TrainerCollection) | GitHub | BSD-3-Clause | 11 |
| [CloudsLetter/Touhou-Project-Mod](https://github.com/CloudsLetter/Touhou-Project-Mod) | GitHub | MIT | 12 |
| [FuwaFuwaTail/game-tables](https://github.com/FuwaFuwaTail/game-tables) | GitHub | MIT | 6 |
| [ObsceneNameHere/CheatTables](https://github.com/ObsceneNameHere/CheatTables) | GitHub | GPL-3.0 | 23 |
| [zard777/Hacking_game_bunker](https://github.com/zard777/Hacking_game_bunker) | GitHub | MIT | 30 |
| [pilot2254/cheat-tables](https://github.com/pilot2254/cheat-tables) | GitHub | MIT | 11 |
| [ichir0roie/cheat_engine_files](https://github.com/ichir0roie/cheat_engine_files) | GitHub | BSD-2-Clause | 29 |
| [abarichello/inside-noclip](https://github.com/abarichello/inside-noclip) | GitHub | GPL-3.0 | 1 |
| [abarichello/minininjas-noclip](https://github.com/abarichello/minininjas-noclip) | GitHub | ISC | 1 |
| [TheRedBull/CheatEngine_PickCrafter](https://github.com/TheRedBull/CheatEngine_PickCrafter) | GitHub | MIT | 1 |
| [Jim00000/YuGiOh-Cheat-Table](https://github.com/Jim00000/YuGiOh-Cheat-Table) | GitHub | MIT | 1 |
| [AadityaKandel/IGI-2-Cheat-Engine-Script](https://github.com/AadityaKandel/IGI-2-Cheat-Engine-Script) | GitHub | MIT | 2 |
| [themaoci/BaldursGate3-CheatTable](https://github.com/themaoci/BaldursGate3-CheatTable) | GitHub | GPL-3.0 | 1 |
| [The-Grand-Archives/ARMORED-CORE-VI-CT-TGA](https://github.com/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA) | GitHub | GPL-3.0 | 1 |
| [Adnini983/PvZHB-CheatTables](https://github.com/Adnini983/PvZHB-CheatTables) | GitHub | MIT | 1 |
| [Adnini983/pvzdlc-ctlist](https://github.com/Adnini983/pvzdlc-ctlist) | GitHub | MIT | 2 |
| [CryZe/CheatTables](https://github.com/CryZe/CheatTables) | GitHub | sin licencia | 19 |
| [atul1503/Cheat-Engine-Tables](https://github.com/atul1503/Cheat-Engine-Tables) | GitHub | sin licencia | 64 |
| [ken1882/CheatTables](https://github.com/ken1882/CheatTables) | GitHub | sin licencia | 86 |
| [grasmanek94/cheat-tables](https://github.com/grasmanek94/cheat-tables) | GitHub | sin licencia | 114 |
| [xXKronosLeeXx/CE-Cheat-Tables](https://github.com/xXKronosLeeXx/CE-Cheat-Tables) | GitHub | sin licencia | 215 |
| [thereisnotime/cheat-engine-tables](https://github.com/thereisnotime/cheat-engine-tables) | GitHub | sin licencia | 52 |
| [davidknapik/My_Cheat_Tables](https://github.com/davidknapik/My_Cheat_Tables) | GitHub | sin licencia | 49 |
| [tranthangminh/Cheat-Engine-Tables-for-Games](https://github.com/tranthangminh/Cheat-Engine-Tables-for-Games) | GitHub | sin licencia | 52 |
| [Wulf2k/Game-MemLocs](https://github.com/Wulf2k/Game-MemLocs) | GitHub | sin licencia | 28 |
| [ReclaimerShawn/Stuff-I-Made](https://github.com/ReclaimerShawn/Stuff-I-Made) | GitHub | sin licencia | 16 |
| [Jesuszilla/cheatengine-scripts](https://github.com/Jesuszilla/cheatengine-scripts) | GitHub | sin licencia | 5 |
| [framedsc/framedsc.github.io](https://github.com/framedsc/framedsc.github.io) | GitHub | sin licencia | 341 |
| [CelestialCosmic/ctTables](https://github.com/CelestialCosmic/ctTables) | GitHub | sin licencia | 37 |
| [tduva/CheatEngine-Tables](https://github.com/tduva/CheatEngine-Tables) | GitHub | sin licencia | 6 |
| [dsasmblr/cheat-engine](https://github.com/dsasmblr/cheat-engine) | GitHub | sin licencia | 5 |
| [sub1to/cheat_tables](https://github.com/sub1to/cheat_tables) | GitHub | sin licencia | 7 |
| [MBRKiNG/CE-Tables](https://github.com/MBRKiNG/CE-Tables) | GitHub | sin licencia | 31 |
| [Eggertron/CheatEngine](https://github.com/Eggertron/CheatEngine) | GitHub | sin licencia | 55 |
| [crazydw4rf/ce-scripts](https://github.com/crazydw4rf/ce-scripts) | GitHub | sin licencia | 9 |
| [Kemui52/CTLibrary](https://github.com/Kemui52/CTLibrary) | GitHub | sin licencia | 6 |
| [ethanwp28/cheat-engine-achievement-unlockers](https://github.com/ethanwp28/cheat-engine-achievement-unlockers) | GitHub | sin licencia | 3 |
| [my-games-backup/my-cheat-engine-tables](https://gitlab.com/my-games-backup/my-cheat-engine-tables) | GitLab | sin licencia | 7 |
| [viktorcpp/Grim-Dawn](https://gitlab.com/viktorcpp/Grim-Dawn) | GitLab | MIT | 1 |
