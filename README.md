# Zona Mods · Tablas de Cheat Engine

Recopilación de **7198 tablas de Cheat Engine (`.CT`) para juegos single-player en Windows**, preparada como fuente automática del servidor de trainers de Zona Mods.

Solo están las tablas que el importador de Zona Mods convierte en al menos un cheat que la app puede ejecutar. Cada archivo es una **copia sin modificar** del original.

## Cómo usarlo en Zona Mods

El servidor coge como mucho 200 archivos por fuente, así que las tablas van repartidas en 36 lotes. En el panel (**Fuentes automáticas**) añade una fuente por lote:

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
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-10
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-11
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-12
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-13
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-14
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-15
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-16
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-17
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-18
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-19
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-20
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-21
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-22
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-23
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-24
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-25
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-26
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-27
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-28
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-29
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-30
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-31
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-32
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-33
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-34
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-35
https://github.com/carbollo/zona-mods-tablas/tree/main/lote-36
```

Conviene añadirlas con **Publicar** desactivado y revisar lo importado antes de publicarlo. Las tablas nunca cambian de lote: las nuevas se añaden al último o abren otro.

## Estructura

```
lote-NN/
  <autor>__<repositorio>/
    ORIGEN.md        enlace al original y licencia
    LICENSE          la del autor, si la tiene
    *.CT             sus tablas
INDICE.md            todas las tablas: juego, proceso, cheats utilizables y enlace al original
manifiesto.tsv       de dónde sale cada archivo (lo usa el script que mantiene el repositorio)
```

## Qué se deja fuera

- **Juegos online, con servidor o de navegador** (GTA V/FiveM, Halo MCC, Counter-Strike, StarCraft II, Warcraft III, Battlefield, Call of Duty, Forza Horizon, Left 4 Dead, MMO, juegos de Facebook y Flash…). Zona Mods es solo para partidas offline y se niega a conectarse si detecta un anticheat.
- Tablas duplicadas (mismo contenido en varios repositorios) y archivos de más de 8 MB, que el servidor no descarga.

## Autores y licencias

Todo el mérito es de sus autores. Este repositorio solo reúne y filtra su trabajo; las tablas siguen bajo las condiciones de cada original, y las que tienen licencia la conservan en su carpeta. Las del archivo histórico del foro de Cheat Engine (Hexorg, David-Honisch) proceden de las tablas que su autor, Dark Byte, cedió para archivarlas.

**¿Eres autor de alguna de estas tablas y prefieres que no esté aquí?** Abre una *issue* y la retiro.

| Origen | Licencia | Tablas |
|---|---|---|
| [Hexorg/CheatEngineTables](https://github.com/Hexorg/CheatEngineTables) | sin licencia | 3575 |
| [framedsc/framedsc.github.io](https://github.com/framedsc/framedsc.github.io) | sin licencia | 341 |
| [themaoci/Sintrix-Dump-Ct](https://github.com/themaoci/Sintrix-Dump-Ct) | sin licencia | 316 |
| [David-Honisch/CheatsAndTricks](https://github.com/David-Honisch/CheatsAndTricks) | sin licencia | 241 |
| [xXKronosLeeXx/CE-Cheat-Tables](https://github.com/xXKronosLeeXx/CE-Cheat-Tables) | sin licencia | 215 |
| [bbfox0703/Mydev-Cheat-Engine-Tables](https://github.com/bbfox0703/Mydev-Cheat-Engine-Tables) | GPL-3.0 | 149 |
| [Daniel-Lobo/WineHooks](https://github.com/Daniel-Lobo/WineHooks) | sin licencia | 130 |
| [ragnaroks/CheatTables](https://github.com/ragnaroks/CheatTables) | AGPL-3.0 | 124 |
| [grasmanek94/cheat-tables](https://github.com/grasmanek94/cheat-tables) | sin licencia | 114 |
| [ken1882/CheatTables](https://github.com/ken1882/CheatTables) | sin licencia | 86 |
| [ryu-highabusa/COMDATsamba](https://github.com/ryu-highabusa/COMDATsamba) | sin licencia | 70 |
| [sl3av/ce-tables](https://github.com/sl3av/ce-tables) | sin licencia | 67 |
| [atul1503/Cheat-Engine-Tables](https://github.com/atul1503/Cheat-Engine-Tables) | sin licencia | 63 |
| [Eggertron/CheatEngine](https://github.com/Eggertron/CheatEngine) | sin licencia | 55 |
| [berthrage/DMC3-Crimson](https://github.com/berthrage/DMC3-Crimson) | MIT | 55 |
| [thereisnotime/cheat-engine-tables](https://github.com/thereisnotime/cheat-engine-tables) | sin licencia | 52 |
| [tranthangminh/Cheat-Engine-Tables-for-Games](https://github.com/tranthangminh/Cheat-Engine-Tables-for-Games) | sin licencia | 52 |
| [davidknapik/My_Cheat_Tables](https://github.com/davidknapik/My_Cheat_Tables) | sin licencia | 49 |
| [tuunowy/Yet-Another-Kindred-Blades-Mod-YAKBM-](https://github.com/tuunowy/Yet-Another-Kindred-Blades-Mod-YAKBM-) | sin licencia | 47 |
| [jisopo/CheatEngineTables](https://github.com/jisopo/CheatEngineTables) | LGPL | 45 |
| [eArmada8/kiseki_ce](https://github.com/eArmada8/kiseki_ce) | GPL-3.0 | 38 |
| [CelestialCosmic/ctTables](https://github.com/CelestialCosmic/ctTables) | sin licencia | 37 |
| [MBRKiNG/CE-Tables](https://github.com/MBRKiNG/CE-Tables) | sin licencia | 31 |
| [zard777/Hacking_game_bunker](https://github.com/zard777/Hacking_game_bunker) | MIT | 30 |
| [ichir0roie/cheat_engine_files](https://github.com/ichir0roie/cheat_engine_files) | BSD-2-Clause | 29 |
| [Wulf2k/Game-MemLocs](https://github.com/Wulf2k/Game-MemLocs) | sin licencia | 28 |
| [ObsceneNameHere/CheatTables](https://github.com/ObsceneNameHere/CheatTables) | GPL-3.0 | 23 |
| [Sora3100/Tales_of_Cheat_Tables](https://github.com/Sora3100/Tales_of_Cheat_Tables) | GPL-3.0 | 22 |
| [BoisterousGaming/Dark-Souls-III-Cheat-Engine-Guide](https://github.com/BoisterousGaming/Dark-Souls-III-Cheat-Engine-Guide) | sin licencia | 22 |
| [JakeMR2/Jake-s-TXR-Resources-and-Research](https://github.com/JakeMR2/Jake-s-TXR-Resources-and-Research) | sin licencia | 20 |
| [CryZe/CheatTables](https://github.com/CryZe/CheatTables) | sin licencia | 19 |
| [AnticOwl/anticowl.github.io](https://github.com/AnticOwl/anticowl.github.io) | sin licencia | 19 |
| [HakuyaNiji/CheatEngineTables](https://github.com/HakuyaNiji/CheatEngineTables) | sin licencia | 18 |
| [metal-crow/Dark-Souls-1-Overhaul](https://github.com/metal-crow/Dark-Souls-1-Overhaul) | AGPL-3.0 | 17 |
| [rajairfanahmed/pc-games-with-trainer-and-cheat-codes](https://github.com/rajairfanahmed/pc-games-with-trainer-and-cheat-codes) | sin licencia | 17 |
| [ReclaimerShawn/Stuff-I-Made](https://github.com/ReclaimerShawn/Stuff-I-Made) | sin licencia | 16 |
| [r3sus/cheads](https://github.com/r3sus/cheads) | sin licencia | 15 |
| [RichardFranksComputer/fdny_info](https://github.com/RichardFranksComputer/fdny_info) | sin licencia | 14 |
| [gmastergreatee/GameCheatFiles](https://github.com/gmastergreatee/GameCheatFiles) | sin licencia | 14 |
| [kapdap/re-cvx-tools](https://github.com/kapdap/re-cvx-tools) | sin licencia | 13 |
| [mrowrpurr/MyCheatEngineTables](https://github.com/mrowrpurr/MyCheatEngineTables) | ISC | 13 |
| [CloudsLetter/Touhou-Project-Mod](https://github.com/CloudsLetter/Touhou-Project-Mod) | MIT | 12 |
| [Borshig/AllCheats](https://github.com/Borshig/AllCheats) | sin licencia | 12 |
| [ParadoxEpoch/RatchetHax](https://github.com/ParadoxEpoch/RatchetHax) | GPL-3.0 | 12 |
| [rjgabel/watches](https://github.com/rjgabel/watches) | sin licencia | 12 |
| [inthecatsdreams/cheat-tables](https://github.com/inthecatsdreams/cheat-tables) | GPL-3.0 | 12 |
| [SeulYoung/TrainerCollection](https://github.com/SeulYoung/TrainerCollection) | BSD-3-Clause | 11 |
| [pilot2254/cheat-tables](https://github.com/pilot2254/cheat-tables) | MIT | 11 |
| [DeveloperJose/Mega-Man-X8-Asset-Manager](https://github.com/DeveloperJose/Mega-Man-X8-Asset-Manager) | MIT | 11 |
| [bartlomiejduda/Tools](https://github.com/bartlomiejduda/Tools) | GPL-3.0 | 11 |
| [HenryPDT/AC-Definitive-Parkour-Mod](https://github.com/HenryPDT/AC-Definitive-Parkour-Mod) | sin licencia | 10 |
| [YukiXXL/PS2-modding](https://github.com/YukiXXL/PS2-modding) | sin licencia | 10 |
| [r3sus/Resouls](https://github.com/r3sus/Resouls) | sin licencia | 10 |
| [binaryriper/cheatenginetables](https://github.com/binaryriper/cheatenginetables) | sin licencia | 10 |
| [crazydw4rf/ce-scripts](https://github.com/crazydw4rf/ce-scripts) | sin licencia | 9 |
| [SomeGTAVCCodes/GTA-Vice-City-PS2](https://github.com/SomeGTAVCCodes/GTA-Vice-City-PS2) | sin licencia | 9 |
| [W1thoutD0ubt/PVZGarageMod](https://github.com/W1thoutD0ubt/PVZGarageMod) | LGPL | 9 |
| [chochang262/cheattables](https://github.com/chochang262/cheattables) | sin licencia | 9 |
| [Wahgew/CheatEngine-CheatTables](https://github.com/Wahgew/CheatEngine-CheatTables) | sin licencia | 8 |
| [junehappylove/june.everything](https://github.com/junehappylove/june.everything) | sin licencia | 8 |
| [soniic7/cheat-tables](https://github.com/soniic7/cheat-tables) | GPL-3.0 | 8 |
| [my-games-backup/my-cheat-engine-tables](https://gitlab.com/my-games-backup/my-cheat-engine-tables) | sin licencia | 7 |
| [sub1to/cheat_tables](https://github.com/sub1to/cheat_tables) | sin licencia | 7 |
| [FransBouma/InjectableGenericCameraSystem](https://github.com/FransBouma/InjectableGenericCameraSystem) | BSD-2-Clause | 7 |
| [ItsAllAboutTheCode/save-converters](https://github.com/ItsAllAboutTheCode/save-converters) | GPL-3.0 | 7 |
| [StyGame/feiche_history_rubbish](https://github.com/StyGame/feiche_history_rubbish) | sin licencia | 7 |
| [daufme/KAIROCHEAT](https://github.com/daufme/KAIROCHEAT) | sin licencia | 7 |
| [FuwaFuwaTail/game-tables](https://github.com/FuwaFuwaTail/game-tables) | MIT | 6 |
| [tduva/CheatEngine-Tables](https://github.com/tduva/CheatEngine-Tables) | sin licencia | 6 |
| [Kemui52/CTLibrary](https://github.com/Kemui52/CTLibrary) | sin licencia | 6 |
| [DeathHound6/CheatTables](https://github.com/DeathHound6/CheatTables) | sin licencia | 6 |
| [Naitrate/EnigmaFix](https://github.com/Naitrate/EnigmaFix) | MIT | 6 |
| [dogbbc/-](https://github.com/dogbbc/-) | sin licencia | 6 |
| [fusigi0930/game_script](https://github.com/fusigi0930/game_script) | sin licencia | 6 |
| [YYLMZXC/nklua](https://github.com/YYLMZXC/nklua) | sin licencia | 6 |
| [legnaleurc/junkcode](https://github.com/legnaleurc/junkcode) | sin licencia | 6 |
| [themaoci/Game-Cheat-Tables-CE-](https://github.com/themaoci/Game-Cheat-Tables-CE-) | sin licencia | 6 |
| [linkz64/cheat-engine-scripts](https://github.com/linkz64/cheat-engine-scripts) | sin licencia | 6 |
| [Jesuszilla/cheatengine-scripts](https://github.com/Jesuszilla/cheatengine-scripts) | sin licencia | 5 |
| [dsasmblr/cheat-engine](https://github.com/dsasmblr/cheat-engine) | sin licencia | 5 |
| [Homer88/GTA2_RE](https://github.com/Homer88/GTA2_RE) | Apache-2.0 | 5 |
| [NyaaCaster/NyaaTrainer](https://github.com/NyaaCaster/NyaaTrainer) | MIT | 5 |
| [SailorSat/daytona-utils](https://github.com/SailorSat/daytona-utils) | MIT | 5 |
| [TCRoid/My-CheatEngine-Table](https://github.com/TCRoid/My-CheatEngine-Table) | sin licencia | 5 |
| [Thermospore/Scene-Files](https://github.com/Thermospore/Scene-Files) | sin licencia | 5 |
| [aldo-arch/Cheats-Cheat-Engine-](https://github.com/aldo-arch/Cheats-Cheat-Engine-) | sin licencia | 5 |
| [asd9176506911298/Cheat-Engine-CT](https://github.com/asd9176506911298/Cheat-Engine-CT) | sin licencia | 5 |
| [nttlong/cheat-engine](https://github.com/nttlong/cheat-engine) | sin licencia | 5 |
| [erfg12/CSharp-Game-Trainers](https://github.com/erfg12/CSharp-Game-Trainers) | sin licencia | 5 |
| [AadityaKandel/BB-RACING-CHEAT-ENGINE-SCRIPT](https://github.com/AadityaKandel/BB-RACING-CHEAT-ENGINE-SCRIPT) | MIT | 4 |
| [CJBok/Cheat-Tables](https://github.com/CJBok/Cheat-Tables) | sin licencia | 4 |
| [JasonGoemaat/CheatEngineMonoHelper](https://github.com/JasonGoemaat/CheatEngineMonoHelper) | MIT | 4 |
| [KCreator/Earth-Defence-Force-Documentation](https://github.com/KCreator/Earth-Defence-Force-Documentation) | sin licencia | 4 |
| [Liftu/PwnAdventure3-Game-Hacking](https://github.com/Liftu/PwnAdventure3-Game-Hacking) | sin licencia | 4 |
| [LXanii/Game-Address-Pointers](https://github.com/LXanii/Game-Address-Pointers) | MIT | 4 |
| [Miuzarte/MyCheatTables](https://github.com/Miuzarte/MyCheatTables) | MIT | 4 |
| [S2-modders/Settlers-DNG-Patches](https://github.com/S2-modders/Settlers-DNG-Patches) | GPL-3.0 | 4 |
| [SKevo18/idlemod](https://github.com/SKevo18/idlemod) | MIT | 4 |
| [SomeGTAVCCodes/GTA-San_Andreas-PS2](https://github.com/SomeGTAVCCodes/GTA-San_Andreas-PS2) | sin licencia | 4 |
| [angelamx/Essentials-2](https://github.com/angelamx/Essentials-2) | sin licencia | 4 |
| [deavers/re-dojo](https://github.com/deavers/re-dojo) | MIT | 4 |
| [mouksx/Toy-Story-2-Modding](https://github.com/mouksx/Toy-Story-2-Modding) | sin licencia | 4 |
| [my-repositories/GameTrainer](https://github.com/my-repositories/GameTrainer) | MIT | 4 |
| [postrazh/PEL2](https://github.com/postrazh/PEL2) | sin licencia | 4 |
| [fullsize/ce_scripts](https://github.com/fullsize/ce_scripts) | sin licencia | 4 |
| [popruns/pop.cheattables](https://github.com/popruns/pop.cheattables) | sin licencia | 4 |
| [Zhiqing-Xu/EXE](https://github.com/Zhiqing-Xu/EXE) | sin licencia | 4 |
| [zupremacy/z-nation](https://github.com/zupremacy/z-nation) | sin licencia | 4 |
| [AndreLouisIssa/Borderlands-Cheat-Tables](https://github.com/AndreLouisIssa/Borderlands-Cheat-Tables) | sin licencia | 3 |
| [ethanwp28/cheat-engine-achievement-unlockers](https://github.com/ethanwp28/cheat-engine-achievement-unlockers) | sin licencia | 3 |
| [Kemui52/EDF-Doc-Storage](https://github.com/Kemui52/EDF-Doc-Storage) | sin licencia | 3 |
| [Lensual/NeteaseMusicLrcHelper](https://github.com/Lensual/NeteaseMusicLrcHelper) | sin licencia | 3 |
| [Lxy417165709/myGo](https://github.com/Lxy417165709/myGo) | sin licencia | 3 |
| [Nighticus/URWME](https://github.com/Nighticus/URWME) | sin licencia | 3 |
| [RezaHanifKurniawan/Cheat-Tabel-PES17-21-SPFL-24](https://github.com/RezaHanifKurniawan/Cheat-Tabel-PES17-21-SPFL-24) | sin licencia | 3 |
| [Ricardo-Tu/ApplicationExtension](https://github.com/Ricardo-Tu/ApplicationExtension) | sin licencia | 3 |
| [Squ1ggs/Scooters-toolbox-V2](https://github.com/Squ1ggs/Scooters-toolbox-V2) | MIT | 3 |
| [fidel-bello/camera-angles](https://github.com/fidel-bello/camera-angles) | MIT | 3 |
| [glowmoss/Cheat-Tables](https://github.com/glowmoss/Cheat-Tables) | sin licencia | 3 |
| [jjcho849/Phasmophobia-Cheat-Engine-Hacking](https://github.com/jjcho849/Phasmophobia-Cheat-Engine-Hacking) | sin licencia | 3 |
| [jmtdev0/life-is-strange-free-camera](https://github.com/jmtdev0/life-is-strange-free-camera) | sin licencia | 3 |
| [ken1882/Trainers](https://github.com/ken1882/Trainers) | Apache-2.0 | 3 |
| [krymzone/Half-Life_CheatTables](https://github.com/krymzone/Half-Life_CheatTables) | sin licencia | 3 |
| [pcrock99/d1](https://github.com/pcrock99/d1) | sin licencia | 3 |
| [yoratoni/bge-widescreen-fix](https://github.com/yoratoni/bge-widescreen-fix) | otra (ver LICENSE) | 3 |
| [zzamizz/weed-sheet](https://github.com/zzamizz/weed-sheet) | sin licencia | 3 |
| [JonathanDotCel/speedrun_tools_for_portal_1_and_2](https://github.com/JonathanDotCel/speedrun_tools_for_portal_1_and_2) | sin licencia | 3 |
| [e4ac/ce-tables](https://github.com/e4ac/ce-tables) | sin licencia | 3 |
| [earmada8/gust_ce](https://github.com/earmada8/gust_ce) | GPL-3.0 | 3 |
| [glowmoss/remove-vhs-effect](https://github.com/glowmoss/remove-vhs-effect) | sin licencia | 3 |
| [tehzz/ssb64-utils](https://github.com/tehzz/ssb64-utils) | sin licencia | 3 |
| [AadityaKandel/IGI-2-Cheat-Engine-Script](https://github.com/AadityaKandel/IGI-2-Cheat-Engine-Script) | MIT | 2 |
| [Adnini983/pvzdlc-ctlist](https://github.com/Adnini983/pvzdlc-ctlist) | MIT | 2 |
| [1233213f/ct1](https://github.com/1233213f/ct1) | sin licencia | 2 |
| [67-6f-64/Rebirth95.Server](https://github.com/67-6f-64/Rebirth95.Server) | sin licencia | 2 |
| [AA2Hackanon/AA2Face](https://github.com/AA2Hackanon/AA2Face) | sin licencia | 2 |
| [Cyril-Meyer/ArtOfRallyTK](https://github.com/Cyril-Meyer/ArtOfRallyTK) | MIT | 2 |
| [F3rNaNDEZ57/Ferrite](https://github.com/F3rNaNDEZ57/Ferrite) | Apache-2.0 | 2 |
| [Glorblach/CheatEngineTables](https://github.com/Glorblach/CheatEngineTables) | sin licencia | 2 |
| [LBALab/LBATrainer](https://github.com/LBALab/LBATrainer) | sin licencia | 2 |
| [Ohdmire/oj](https://github.com/Ohdmire/oj) | sin licencia | 2 |
| [Petsku01/Theory](https://github.com/Petsku01/Theory) | sin licencia | 2 |
| [Robot/robot](https://github.com/Robot/robot) | otra (ver LICENSE) | 2 |
| [RstursOC/wechat_dll_rs](https://github.com/RstursOC/wechat_dll_rs) | sin licencia | 2 |
| [ShadowTheHedgehogHacking/shadow-symbols-and-dmw](https://github.com/ShadowTheHedgehogHacking/shadow-symbols-and-dmw) | sin licencia | 2 |
| [Smoker1/RetroArch-174-and-above-Cheats](https://github.com/Smoker1/RetroArch-174-and-above-Cheats) | sin licencia | 2 |
| [Therdel/cssHack](https://github.com/Therdel/cssHack) | GPL-3.0 | 2 |
| [TheShenJi/freepvzcheat](https://github.com/TheShenJi/freepvzcheat) | sin licencia | 2 |
| [amadare42/HunterPie.AutoHunter](https://github.com/amadare42/HunterPie.AutoHunter) | sin licencia | 2 |
| [axpokl/FTLGame_Cheat](https://github.com/axpokl/FTLGame_Cheat) | MIT | 2 |
| [cheeseandcereal/ToyStory2Resources](https://github.com/cheeseandcereal/ToyStory2Resources) | sin licencia | 2 |
| [coder114514/casio](https://github.com/coder114514/casio) | sin licencia | 2 |
| [crabshank/PES_Cheat_Tables](https://github.com/crabshank/PES_Cheat_Tables) | sin licencia | 2 |
| [cyberspyde/bfme](https://github.com/cyberspyde/bfme) | sin licencia | 2 |
| [dragonloverlord/DebugDumpPile](https://github.com/dragonloverlord/DebugDumpPile) | sin licencia | 2 |
| [elanjcoop/Elan-2K-Mod](https://github.com/elanjcoop/Elan-2K-Mod) | sin licencia | 2 |
| [electrogecko/UYA_pyTools](https://github.com/electrogecko/UYA_pyTools) | GPL-3.0 | 2 |
| [exodus122/zelda_3ds_heap_viewer](https://github.com/exodus122/zelda_3ds_heap_viewer) | sin licencia | 2 |
| [YSakhno/cheatengine-tables](https://github.com/YSakhno/cheatengine-tables) | sin licencia | 2 |
| [hyperzlib/Awesome-Coyote-Game-Hub](https://github.com/hyperzlib/Awesome-Coyote-Game-Hub) | sin licencia | 2 |
| [jonyTF/Dying-Light-TAS](https://github.com/jonyTF/Dying-Light-TAS) | sin licencia | 2 |
| [jsaidoru/casio-tools](https://github.com/jsaidoru/casio-tools) | sin licencia | 2 |
| [jubin-park/RPGMakerHook](https://github.com/jubin-park/RPGMakerHook) | MIT | 2 |
| [landonAL/dotfiles](https://github.com/landonAL/dotfiles) | sin licencia | 2 |
| [nlhans/SimShift](https://github.com/nlhans/SimShift) | MIT | 2 |
| [nonumbershere/GoogleMods](https://github.com/nonumbershere/GoogleMods) | sin licencia | 2 |
| [riz7861/TPHD-Cemu-Trainer](https://github.com/riz7861/TPHD-Cemu-Trainer) | sin licencia | 2 |
| [rodrigo-sssilva/STrainer](https://github.com/rodrigo-sssilva/STrainer) | sin licencia | 2 |
| [talktokim/AutoTLBB](https://github.com/talktokim/AutoTLBB) | MIT | 2 |
| [un4ckn0wl3z/GameHackingBookLab](https://github.com/un4ckn0wl3z/GameHackingBookLab) | sin licencia | 2 |
| [unkmc/TkMemory](https://github.com/unkmc/TkMemory) | GPL-3.0 | 2 |
| [yo1995/nba2k-shotchart-project](https://github.com/yo1995/nba2k-shotchart-project) | GPL-3.0 | 2 |
| [zarroboogs/p5-ct](https://github.com/zarroboogs/p5-ct) | sin licencia | 2 |
| [01uan/retro-helpers](https://github.com/01uan/retro-helpers) | sin licencia | 2 |
| [Archiver-of-Triviality/Tekken-Tables](https://github.com/Archiver-of-Triviality/Tekken-Tables) | sin licencia | 2 |
| [FormatX66/medic-gpt-shared](https://github.com/FormatX66/medic-gpt-shared) | sin licencia | 2 |
| [Tedward747/Cheat-Engine-Tables](https://github.com/Tedward747/Cheat-Engine-Tables) | sin licencia | 2 |
| [WolfGamerYT/Undertale-Hacking](https://github.com/WolfGamerYT/Undertale-Hacking) | sin licencia | 2 |
| [abgache/rise-of-nations-cheats](https://github.com/abgache/rise-of-nations-cheats) | sin licencia | 2 |
| [gitDanilo/LoP-Bars](https://github.com/gitDanilo/LoP-Bars) | sin licencia | 2 |
| [h0p3fu1/cheattables](https://github.com/h0p3fu1/cheattables) | sin licencia | 2 |
| [ifpcd/ct_tables](https://github.com/ifpcd/ct_tables) | sin licencia | 2 |
| [karniverse/cheat-tables](https://github.com/karniverse/cheat-tables) | sin licencia | 2 |
| [krymzone/ds-personal_tables](https://github.com/krymzone/ds-personal_tables) | sin licencia | 2 |
| [kyadlfiles/kya_dl_cheat_tables](https://github.com/kyadlfiles/kya_dl_cheat_tables) | sin licencia | 2 |
| [lucacicada/dark-chronicle-reverse-engineering](https://github.com/lucacicada/dark-chronicle-reverse-engineering) | MIT | 2 |
| [sjkim1127/Everplanet_Reverse_Engineering](https://github.com/sjkim1127/Everplanet_Reverse_Engineering) | sin licencia | 2 |
| [taitan666/cheatengineagent](https://github.com/taitan666/cheatengineagent) | MIT | 2 |
| [thereisnotime/tint-cheats](https://github.com/thereisnotime/tint-cheats) | MIT | 2 |
| [valgoldun/fly-corp-hack](https://github.com/valgoldun/fly-corp-hack) | sin licencia | 2 |
| [abarichello/inside-noclip](https://github.com/abarichello/inside-noclip) | GPL-3.0 | 1 |
| [abarichello/minininjas-noclip](https://github.com/abarichello/minininjas-noclip) | ISC | 1 |
| [Adnini983/PvZHB-CheatTables](https://github.com/Adnini983/PvZHB-CheatTables) | MIT | 1 |
| [Jim00000/YuGiOh-Cheat-Table](https://github.com/Jim00000/YuGiOh-Cheat-Table) | MIT | 1 |
| [The-Grand-Archives/ARMORED-CORE-VI-CT-TGA](https://github.com/The-Grand-Archives/ARMORED-CORE-VI-CT-TGA) | GPL-3.0 | 1 |
| [themaoci/BaldursGate3-CheatTable](https://github.com/themaoci/BaldursGate3-CheatTable) | GPL-3.0 | 1 |
| [TheRedBull/CheatEngine_PickCrafter](https://github.com/TheRedBull/CheatEngine_PickCrafter) | MIT | 1 |
| [AadityaKandel/Hill-Climb-Racing-Trainer-CheatEngine](https://github.com/AadityaKandel/Hill-Climb-Racing-Trainer-CheatEngine) | sin licencia | 1 |
| [Aib0t/blur-community-wiki](https://github.com/Aib0t/blur-community-wiki) | sin licencia | 1 |
| [AstralKitsune/Joymania](https://github.com/AstralKitsune/Joymania) | sin licencia | 1 |
| [Avery3R/WRCGModTools](https://github.com/Avery3R/WRCGModTools) | sin licencia | 1 |
| [Banon-Labs/er-mods-rs](https://github.com/Banon-Labs/er-mods-rs) | sin licencia | 1 |
| [Belson112/warhook](https://github.com/Belson112/warhook) | MIT | 1 |
| [Bituvo/GDDocs](https://github.com/Bituvo/GDDocs) | sin licencia | 1 |
| [Bo-roman/DSIII-RL](https://github.com/Bo-roman/DSIII-RL) | LGPL | 1 |
| [ConnorLanglois/lolbot](https://github.com/ConnorLanglois/lolbot) | sin licencia | 1 |
| [CryZe/furious-fish-auto-splitter](https://github.com/CryZe/furious-fish-auto-splitter) | MIT | 1 |
| [Cyb10101/notes](https://github.com/Cyb10101/notes) | sin licencia | 1 |
| [viktorcpp/Grim-Dawn](https://gitlab.com/viktorcpp/Grim-Dawn) | MIT | 1 |
| [Delean-Mafra/Caesar3](https://github.com/Delean-Mafra/Caesar3) | Creative Commons | 1 |
| [DemoJameson/HollowKnightTasInfo](https://github.com/DemoJameson/HollowKnightTasInfo) | sin licencia | 1 |
| [Denhonator/Load-Removers-and-Mods](https://github.com/Denhonator/Load-Removers-and-Mods) | MIT | 1 |
| [DordyBalbez/Pokemon-Catch-Probability](https://github.com/DordyBalbez/Pokemon-Catch-Probability) | sin licencia | 1 |
| [Equiduck/Cheat-Tables](https://github.com/Equiduck/Cheat-Tables) | sin licencia | 1 |
| [Ev0lt/pvz_patch](https://github.com/Ev0lt/pvz_patch) | Apache-2.0 | 1 |
| [FlyDragonW/Break-All-CTF-2024-Reverse](https://github.com/FlyDragonW/Break-All-CTF-2024-Reverse) | sin licencia | 1 |
| [GabriWar/animalwellcheat](https://github.com/GabriWar/animalwellcheat) | sin licencia | 1 |
| [Galidar/DSSeamlessCoop](https://github.com/Galidar/DSSeamlessCoop) | MIT | 1 |
| [Game-Hacking-Village/cpp_external](https://github.com/Game-Hacking-Village/cpp_external) | sin licencia | 1 |
| [Gluton-Official/FLRPC](https://github.com/Gluton-Official/FLRPC) | MIT | 1 |
| [INTP-fei/work](https://github.com/INTP-fei/work) | sin licencia | 1 |
| [JaimeFSJ/TFM-MUSTIC](https://github.com/JaimeFSJ/TFM-MUSTIC) | sin licencia | 1 |
| [KaleidSkylark/JRX-JQIARQHXUHE-JHQYDUH](https://github.com/KaleidSkylark/JRX-JQIARQHXUHE-JHQYDUH) | sin licencia | 1 |
| [KimochiYikes/MikuMikuDance-Mods](https://github.com/KimochiYikes/MikuMikuDance-Mods) | sin licencia | 1 |
| [Krys-Kus/maturita](https://github.com/Krys-Kus/maturita) | LGPL | 1 |
| [LE3TGAM3R/I2T2](https://github.com/LE3TGAM3R/I2T2) | MIT | 1 |
| [LonLon-Labs/SSHD_APWorld](https://github.com/LonLon-Labs/SSHD_APWorld) | AGPL-3.0 | 1 |
| [LuBuCake/GameX](https://github.com/LuBuCake/GameX) | GPL-3.0 | 1 |
| [MaurycyBartczak/MobilnyMechanik2.0](https://github.com/MaurycyBartczak/MobilnyMechanik2.0) | MIT | 1 |
| [Naitrate/AriseFix](https://github.com/Naitrate/AriseFix) | GPL-3.0 | 1 |
| [NotMadscientist/CCCaster](https://github.com/NotMadscientist/CCCaster) | sin licencia | 1 |
| [OwlLukas/Components](https://github.com/OwlLukas/Components) | sin licencia | 1 |
| [Perlence/gpvi](https://github.com/Perlence/gpvi) | BSD-3-Clause | 1 |
| [Prekzursil/SWFOC-Mod-Menu](https://github.com/Prekzursil/SWFOC-Mod-Menu) | MIT | 1 |
| [RetroHero/MHPSP-Cheats](https://github.com/RetroHero/MHPSP-Cheats) | sin licencia | 1 |
| [Sleepy93/Driv3R-Multiplayer](https://github.com/Sleepy93/Driv3R-Multiplayer) | sin licencia | 1 |
| [SquareMan/cosmic-shake-auto-splitter](https://github.com/SquareMan/cosmic-shake-auto-splitter) | Apache-2.0 | 1 |
| [SuiMachine/AVP--2010--FOV-Changer](https://github.com/SuiMachine/AVP--2010--FOV-Changer) | sin licencia | 1 |
| [Synthlight/MHWilds-Neuter-Encryption](https://github.com/Synthlight/MHWilds-Neuter-Encryption) | sin licencia | 1 |
| [The-Itach1/CSHacker](https://github.com/The-Itach1/CSHacker) | sin licencia | 1 |
| [TreacherousDev/Silicon](https://github.com/TreacherousDev/Silicon) | Apache-2.0 | 1 |
| [Undertaker-afk/Skinchanger-test](https://github.com/Undertaker-afk/Skinchanger-test) | sin licencia | 1 |
| [Vinjul1704/er-zip-resources](https://github.com/Vinjul1704/er-zip-resources) | sin licencia | 1 |
| [aapplesauc/STrainer-4.2](https://github.com/aapplesauc/STrainer-4.2) | sin licencia | 1 |
| [agehring80/CheatEngine](https://github.com/agehring80/CheatEngine) | sin licencia | 1 |
| [aloyark/NieR-Automata-Practice-Table](https://github.com/aloyark/NieR-Automata-Practice-Table) | MIT | 1 |
| [altair-sossai/30XX-Trainer](https://github.com/altair-sossai/30XX-Trainer) | sin licencia | 1 |
| [andreistoicescu74015/The-Custom-Run](https://github.com/andreistoicescu74015/The-Custom-Run) | sin licencia | 1 |
| [antumce/MMU](https://github.com/antumce/MMU) | otra (ver LICENSE.txt) | 1 |
| [aron-666/Aron-For-TwMs-113-4.0](https://github.com/aron-666/Aron-For-TwMs-113-4.0) | sin licencia | 1 |
| [asubaruwrxsti/GhostOfTsushima](https://github.com/asubaruwrxsti/GhostOfTsushima) | sin licencia | 1 |
| [awildergoose/jazz2](https://github.com/awildergoose/jazz2) | MIT | 1 |
| [bgcwzf/CE_MOD_4_U](https://github.com/bgcwzf/CE_MOD_4_U) | sin licencia | 1 |
| [bscan7/study](https://github.com/bscan7/study) | sin licencia | 1 |
| [captainanderz/Mirrors-Edge-Catalyst-SpeedOMeter](https://github.com/captainanderz/Mirrors-Edge-Catalyst-SpeedOMeter) | sin licencia | 1 |
| [celuaru/structure_hunter](https://github.com/celuaru/structure_hunter) | sin licencia | 1 |
| [ckosmic/CH3AT](https://github.com/ckosmic/CH3AT) | MIT | 1 |
| [clod44/NFSU2Clutch](https://github.com/clod44/NFSU2Clutch) | MIT | 1 |
| [cndofx/mh-rise-ct](https://github.com/cndofx/mh-rise-ct) | MIT | 1 |
| [commonheartwah/PlantWAH](https://github.com/commonheartwah/PlantWAH) | sin licencia | 1 |
| [danjaaron/Diablo1-Trainer](https://github.com/danjaaron/Diablo1-Trainer) | sin licencia | 1 |
| [donnaken15/11UP](https://github.com/donnaken15/11UP) | sin licencia | 1 |
| [donnaken15/HydroMod](https://github.com/donnaken15/HydroMod) | sin licencia | 1 |
| [dreary-dugong/tethergeist_utils](https://github.com/dreary-dugong/tethergeist_utils) | MIT | 1 |
| [eantoniobr/S8-Private](https://github.com/eantoniobr/S8-Private) | sin licencia | 1 |
| [evreqe/everquest](https://github.com/evreqe/everquest) | sin licencia | 1 |
| [firodj/re-sbz](https://github.com/firodj/re-sbz) | sin licencia | 1 |
| [gamesbyian/GRA-EDISNI](https://github.com/gamesbyian/GRA-EDISNI) | sin licencia | 1 |
| [gjchangmu/Spelunky-MEP](https://github.com/gjchangmu/Spelunky-MEP) | MIT | 1 |
| [XavierCruz5106/Cheat-Tables](https://github.com/XavierCruz5106/Cheat-Tables) | sin licencia | 1 |
| [ZAIQuQ/TencentClientReverseLearning](https://github.com/ZAIQuQ/TencentClientReverseLearning) | sin licencia | 1 |
| [Zed-z/c2-mod-loader](https://github.com/Zed-z/c2-mod-loader) | MIT | 1 |
| [ZhangYiXiSucceed/PlantsVsZombiesCE](https://github.com/ZhangYiXiSucceed/PlantsVsZombiesCE) | sin licencia | 1 |
| [Zielasko/Sekiro-Zero](https://github.com/Zielasko/Sekiro-Zero) | GPL-3.0 | 1 |
| [ZoDDeL/CheatEngine-Tables](https://github.com/ZoDDeL/CheatEngine-Tables) | sin licencia | 1 |
| [harryzhangpro/DGLAB-Black-Myth-Wukong](https://github.com/harryzhangpro/DGLAB-Black-Myth-Wukong) | MIT | 1 |
| [heaven-hm/gtlibcpp](https://github.com/heaven-hm/gtlibcpp) | otra (ver LICENSE) | 1 |
| [heaven-hm/project-igi-research](https://github.com/heaven-hm/project-igi-research) | GPL-3.0 | 1 |
| [iccugs/alan_wake_trainer](https://github.com/iccugs/alan_wake_trainer) | sin licencia | 1 |
| [iccugs/bobafett_compiled_with_cheat_table](https://github.com/iccugs/bobafett_compiled_with_cheat_table) | sin licencia | 1 |
| [iccugs/Resident_Evil_7_Trainer](https://github.com/iccugs/Resident_Evil_7_Trainer) | sin licencia | 1 |
| [ithinkandicode/door-kickers-action-squad-mods](https://github.com/ithinkandicode/door-kickers-action-squad-mods) | sin licencia | 1 |
| [januwA/ce-ICEY](https://github.com/januwA/ce-ICEY) | sin licencia | 1 |
| [joric/ootss](https://github.com/joric/ootss) | Unlicense | 1 |
| [josdemmers/Trainer.SuperTux](https://github.com/josdemmers/Trainer.SuperTux) | MIT | 1 |
| [kb1000fx/kb1000fx.github.io](https://github.com/kb1000fx/kb1000fx.github.io) | sin licencia | 1 |
| [kevrgithub/eqmac](https://github.com/kevrgithub/eqmac) | sin licencia | 1 |
| [lilly1987/Sins-of-a-Solar-Empire-II-mods](https://github.com/lilly1987/Sins-of-a-Solar-Empire-II-mods) | sin licencia | 1 |
| [lizeren/Easy-Red-2-Trainer](https://github.com/lizeren/Easy-Red-2-Trainer) | sin licencia | 1 |
| [lord-yoshi/MvC2-CE-Trainer-Script](https://github.com/lord-yoshi/MvC2-CE-Trainer-Script) | sin licencia | 1 |
| [lyufeng000/Hades2-CT](https://github.com/lyufeng000/Hades2-CT) | sin licencia | 1 |
| [meanwhile-labs/legosw-tsc-saves](https://github.com/meanwhile-labs/legosw-tsc-saves) | sin licencia | 1 |
| [mi5hmash/KatanaSaveDataResigner](https://github.com/mi5hmash/KatanaSaveDataResigner) | MIT | 1 |
| [mi5hmash/SL2Bonfire](https://github.com/mi5hmash/SL2Bonfire) | MIT | 1 |
| [mint-choc-chip-skyblade/sshd-tools](https://github.com/mint-choc-chip-skyblade/sshd-tools) | AGPL-3.0 | 1 |
| [mRally2/Most-Wanted-Overhauled](https://github.com/mRally2/Most-Wanted-Overhauled) | sin licencia | 1 |
| [mRally2/TheSupercarRun](https://github.com/mRally2/TheSupercarRun) | sin licencia | 1 |
| [mrDarknessSun/Cheat-Engine-Lua-DirectHookAPI-Menu-D3D](https://github.com/mrDarknessSun/Cheat-Engine-Lua-DirectHookAPI-Menu-D3D) | sin licencia | 1 |
| [muhopensores/dmc4_hook](https://github.com/muhopensores/dmc4_hook) | MIT | 1 |
| [nyanfox87/G4meH4ck1ng](https://github.com/nyanfox87/G4meH4ck1ng) | sin licencia | 1 |
| [nyaThoi/nPublic](https://github.com/nyaThoi/nPublic) | sin licencia | 1 |
| [omnibread/null](https://github.com/omnibread/null) | LGPL | 1 |
| [pedroVril/Cheat-Engine-tables-and-scripts](https://github.com/pedroVril/Cheat-Engine-tables-and-scripts) | MIT | 1 |
| [rainy-seasons/Dishonored-Trainer](https://github.com/rainy-seasons/Dishonored-Trainer) | MIT | 1 |
| [robin-mu/EDGE](https://github.com/robin-mu/EDGE) | sin licencia | 1 |
| [sandycheeks-10/Dissertation](https://github.com/sandycheeks-10/Dissertation) | sin licencia | 1 |
| [seedpodsw/GhostRecon-Wildlands-FPS](https://github.com/seedpodsw/GhostRecon-Wildlands-FPS) | sin licencia | 1 |
| [shadax1/SuperMarisaWorldPrac](https://github.com/shadax1/SuperMarisaWorldPrac) | sin licencia | 1 |
| [speedfuns/okami](https://github.com/speedfuns/okami) | sin licencia | 1 |
| [supersaiyansubtlety/DS-III-CT](https://github.com/supersaiyansubtlety/DS-III-CT) | sin licencia | 1 |
| [tim-tim707/SW_RACER_RE](https://github.com/tim-tim707/SW_RACER_RE) | AGPL-3.0 | 1 |
| [transfairs/A2G-Trainer](https://github.com/transfairs/A2G-Trainer) | sin licencia | 1 |
| [turtle-insect/DQB2](https://github.com/turtle-insect/DQB2) | GPL-3.0 | 1 |
| [ucuckic/dfci-gx](https://github.com/ucuckic/dfci-gx) | sin licencia | 1 |
| [un4ckn0wl3z/winmine.frida](https://github.com/un4ckn0wl3z/winmine.frida) | sin licencia | 1 |
| [vanjac/aodix-repair](https://github.com/vanjac/aodix-repair) | MIT | 1 |
| [xAranaktu/FM21-Cheat-Table](https://github.com/xAranaktu/FM21-Cheat-Table) | MIT | 1 |
| [xyz8848/PVZ-CETable](https://github.com/xyz8848/PVZ-CETable) | sin licencia | 1 |
| [yangyxd/ra2-tool](https://github.com/yangyxd/ra2-tool) | sin licencia | 1 |
| [yugecin/nfsu2-re](https://github.com/yugecin/nfsu2-re) | sin licencia | 1 |
| [yugecin/scmcleoscripts](https://github.com/yugecin/scmcleoscripts) | GPL-3.0 | 1 |
| [360madden/riftreader](https://github.com/360madden/riftreader) | sin licencia | 1 |
| [4aiman/StHAAM](https://github.com/4aiman/StHAAM) | MIT | 1 |
| [4YDnO1/syn-dev-dll](https://github.com/4YDnO1/syn-dev-dll) | sin licencia | 1 |
| [A1rPun/castle-crashers-resource](https://github.com/A1rPun/castle-crashers-resource) | MIT | 1 |
| [Ahram-41/ct_4_palworld](https://github.com/Ahram-41/ct_4_palworld) | sin licencia | 1 |
| [AnnoyingKarma/LearningEverything](https://github.com/AnnoyingKarma/LearningEverything) | sin licencia | 1 |
| [Arefu/Yu-Gi-Oh-Ex](https://github.com/Arefu/Yu-Gi-Oh-Ex) | otra (ver LICENSE-ADDENDUM.md) | 1 |
| [Armonte/wanwan](https://github.com/Armonte/wanwan) | otra (ver LICENSE) | 1 |
| [AScriver/LSWTSS-Adjustable-FOV](https://github.com/AScriver/LSWTSS-Adjustable-FOV) | MIT | 1 |
| [AXR002/group-2-security](https://github.com/AXR002/group-2-security) | sin licencia | 1 |
| [Boleklolo/TombRaider2UltimateCheat](https://github.com/Boleklolo/TombRaider2UltimateCheat) | MIT | 1 |
| [Brok3d3ad/newClitor](https://github.com/Brok3d3ad/newClitor) | sin licencia | 1 |
| [CactusPie/Palworld-DisableBuildingRestrictions](https://github.com/CactusPie/Palworld-DisableBuildingRestrictions) | GPL-3.0 | 1 |
| [DaveUltra/ptle](https://github.com/DaveUltra/ptle) | sin licencia | 1 |
| [Doa6Vr/Doa6Vr](https://github.com/Doa6Vr/Doa6Vr) | sin licencia | 1 |
| [Edgarflc/Only_Climb_Trainer](https://github.com/Edgarflc/Only_Climb_Trainer) | MIT | 1 |
| [Eli-bassoon/TGQMouseMod](https://github.com/Eli-bassoon/TGQMouseMod) | MIT | 1 |
| [ExMingYan/KOFXIII-LuaHack](https://github.com/ExMingYan/KOFXIII-LuaHack) | MIT | 1 |
| [ExpHP/thcrap-patches](https://github.com/ExpHP/thcrap-patches) | sin licencia | 1 |
| [Fatih120/hellsinker-notes](https://github.com/Fatih120/hellsinker-notes) | sin licencia | 1 |
| [FindMuck/SnowRunner_Noclip](https://github.com/FindMuck/SnowRunner_Noclip) | sin licencia | 1 |
| [FottenSC/Scuffle](https://github.com/FottenSC/Scuffle) | MIT | 1 |
| [Gear2ndGandalf/sh2ee-code-builder](https://github.com/Gear2ndGandalf/sh2ee-code-builder) | MIT | 1 |
| [Grimrukh/EldenRingSurvivalMode](https://github.com/Grimrukh/EldenRingSurvivalMode) | sin licencia | 1 |
| [Grimrukh/SoulsModifier](https://github.com/Grimrukh/SoulsModifier) | sin licencia | 1 |
| [HeathHowren/iretable-tools](https://github.com/HeathHowren/iretable-tools) | MIT | 1 |
| [HumanTree92/VENT_Palworld_ModPack](https://github.com/HumanTree92/VENT_Palworld_ModPack) | GPL-3.0 | 1 |
| [J-T-de/CrusaderData](https://github.com/J-T-de/CrusaderData) | MIT | 1 |
| [J31why/ED63Trans](https://github.com/J31why/ED63Trans) | Apache-2.0 | 1 |
| [JihadJackass/CK2-Modded-Achievement-Patcher-MAP](https://github.com/JihadJackass/CK2-Modded-Achievement-Patcher-MAP) | sin licencia | 1 |
| [KodyJKing/ds3-practice-mode](https://github.com/KodyJKing/ds3-practice-mode) | sin licencia | 1 |
| [KodyJKing/spark](https://github.com/KodyJKing/spark) | sin licencia | 1 |
| [Louckinho/MonsterRancher2Span](https://github.com/Louckinho/MonsterRancher2Span) | sin licencia | 1 |
| [LunaMoo/PPSSPP-Cheat-Table](https://github.com/LunaMoo/PPSSPP-Cheat-Table) | sin licencia | 1 |
| [Margen67/stuff](https://github.com/Margen67/stuff) | sin licencia | 1 |
| [MestreLion/GameHelpers](https://github.com/MestreLion/GameHelpers) | sin licencia | 1 |
| [Naitrate/21xMachi9](https://github.com/Naitrate/21xMachi9) | GPL-3.0 | 1 |
| [Puh00/Resident-Evil-5-Trainer](https://github.com/Puh00/Resident-Evil-5-Trainer) | MIT | 1 |
| [ReptarK/MasterH1Z1](https://github.com/ReptarK/MasterH1Z1) | sin licencia | 1 |
| [Shaitz/OpenArenaInternal](https://github.com/Shaitz/OpenArenaInternal) | sin licencia | 1 |
| [Sleepy93/DriverMP](https://github.com/Sleepy93/DriverMP) | sin licencia | 1 |
| [SLKCoding/lfs-rp](https://github.com/SLKCoding/lfs-rp) | sin licencia | 1 |
| [SLoSkady/MECMM](https://github.com/SLoSkady/MECMM) | MIT | 1 |
| [SteffenL/Van-Helsing-game-research](https://github.com/SteffenL/Van-Helsing-game-research) | sin licencia | 1 |
| [SuiMachine/MedalOfHonorFOVChanger](https://github.com/SuiMachine/MedalOfHonorFOVChanger) | sin licencia | 1 |
| [Szar/SA2-Coop](https://github.com/Szar/SA2-Coop) | sin licencia | 1 |
| [Tautellini/Starfield-WeaponFoV-CheatEngine](https://github.com/Tautellini/Starfield-WeaponFoV-CheatEngine) | sin licencia | 1 |
| [TheGrandArchives/DS3CommunityPatch](https://github.com/TheGrandArchives/DS3CommunityPatch) | GPL-3.0 | 1 |
| [TheLettuceClub/BBCF-Sammi](https://github.com/TheLettuceClub/BBCF-Sammi) | sin licencia | 1 |
| [Therdel/mince](https://github.com/Therdel/mince) | sin licencia | 1 |
| [Twig6943/ReplantedMaxxer](https://github.com/Twig6943/ReplantedMaxxer) | GPL-3.0 | 1 |
| [UtterVitriol/Game-Hacking](https://github.com/UtterVitriol/Game-Hacking) | sin licencia | 1 |
| [aadmiqbal/pwnie-island-dll](https://github.com/aadmiqbal/pwnie-island-dll) | sin licencia | 1 |
| [abhijeetadarsh/cttrainer](https://github.com/abhijeetadarsh/cttrainer) | MIT | 1 |
| [aeons-d/crystar-cheat-engine](https://github.com/aeons-d/crystar-cheat-engine) | sin licencia | 1 |
| [andrew101sanders/FF7RebirthFovChanger](https://github.com/andrew101sanders/FF7RebirthFovChanger) | MIT | 1 |
| [antaresjay/freeplay](https://github.com/antaresjay/freeplay) | MIT | 1 |
| [artemis-of-dust/ggst_ct](https://github.com/artemis-of-dust/ggst_ct) | sin licencia | 1 |
| [bahndaten/ujl-cheattable](https://github.com/bahndaten/ujl-cheattable) | sin licencia | 1 |
| [balenaucigasa/Gems-of-War-v9](https://github.com/balenaucigasa/Gems-of-War-v9) | Unlicense | 1 |
| [ben2557/ce-table-sh3](https://github.com/ben2557/ce-table-sh3) | sin licencia | 1 |
| [ben2557/ce-table-sh4](https://github.com/ben2557/ce-table-sh4) | sin licencia | 1 |
| [bobba-v/fell-and-sell-ct](https://github.com/bobba-v/fell-and-sell-ct) | sin licencia | 1 |
| [bramicoatual/re4-2005-internal-trainer](https://github.com/bramicoatual/re4-2005-internal-trainer) | sin licencia | 1 |
| [carterjones/pwnie-island](https://github.com/carterjones/pwnie-island) | BSD-2-Clause | 1 |
| [ceattable/cheat-table](https://github.com/ceattable/cheat-table) | sin licencia | 1 |
| [colonywest/cheatengine](https://github.com/colonywest/cheatengine) | sin licencia | 1 |
| [d3v0psdan/combat-master-internal](https://github.com/d3v0psdan/combat-master-internal) | sin licencia | 1 |
| [danjaaron/fallout1-trainer](https://github.com/danjaaron/fallout1-trainer) | sin licencia | 1 |
| [danjaaron/frostpunk-hack](https://github.com/danjaaron/frostpunk-hack) | sin licencia | 1 |
| [eexpress/bin](https://github.com/eexpress/bin) | sin licencia | 1 |
| [electricalArt/MemoryHackerLib](https://github.com/electricalArt/MemoryHackerLib) | sin licencia | 1 |
| [feradile/sm64coopdx-cheats](https://github.com/feradile/sm64coopdx-cheats) | sin licencia | 1 |
| [freshman2233/spell-brigade-ct](https://github.com/freshman2233/spell-brigade-ct) | sin licencia | 1 |
| [freylaverse/vatucheats](https://github.com/freylaverse/vatucheats) | sin licencia | 1 |
| [gcmaniac/cheat_engine_mod](https://github.com/gcmaniac/cheat_engine_mod) | MIT | 1 |
| [gonthoriandx/the-ogre-table](https://github.com/gonthoriandx/the-ogre-table) | sin licencia | 1 |
| [h0x91b/gta2-resurection](https://github.com/h0x91b/gta2-resurection) | MIT | 1 |
| [he4rtbleed/CaptainHooker](https://github.com/he4rtbleed/CaptainHooker) | MIT | 1 |
| [ibrow19/GGXrdReplayTakeover](https://github.com/ibrow19/GGXrdReplayTakeover) | sin licencia | 1 |
| [iccugs/megamanunlimitedtrainer](https://github.com/iccugs/megamanunlimitedtrainer) | sin licencia | 1 |
| [iccugs/zelda_tp_cemu_trainer](https://github.com/iccugs/zelda_tp_cemu_trainer) | sin licencia | 1 |
| [iHackerJi/GameCheat](https://github.com/iHackerJi/GameCheat) | sin licencia | 1 |
| [im23b-busere/Cheat-Tables](https://github.com/im23b-busere/Cheat-Tables) | sin licencia | 1 |
| [jim00000/chasm-cheat-table](https://github.com/jim00000/chasm-cheat-table) | MIT | 1 |
| [joboyskat/gw2-bot](https://github.com/joboyskat/gw2-bot) | sin licencia | 1 |
| [jubin-park/ppdrow](https://github.com/jubin-park/ppdrow) | MIT | 1 |
| [k-r-o-s/ce-tables](https://github.com/k-r-o-s/ce-tables) | sin licencia | 1 |
| [kalbintion/ddaobcreator](https://github.com/kalbintion/ddaobcreator) | sin licencia | 1 |
| [kohakubeast/holocure-pointer](https://github.com/kohakubeast/holocure-pointer) | sin licencia | 1 |
| [kurtis2221/stuntsmp](https://github.com/kurtis2221/stuntsmp) | sin licencia | 1 |
| [kwwsyk/Elden-Ring-Nightreign-Cheat-Table](https://github.com/kwwsyk/Elden-Ring-Nightreign-Cheat-Table) | sin licencia | 1 |
| [mach-kernel/callisto-trainer](https://github.com/mach-kernel/callisto-trainer) | sin licencia | 1 |
| [majorzero69/mgs3-trainer](https://github.com/majorzero69/mgs3-trainer) | sin licencia | 1 |
| [maluramichael/re-silver](https://github.com/maluramichael/re-silver) | Apache-2.0 | 1 |
| [mmahoney09110/EldenRingEncouragement](https://github.com/mmahoney09110/EldenRingEncouragement) | MIT | 1 |
| [mmfelixfu-maker/l4d2_X_DGlab](https://github.com/mmfelixfu-maker/l4d2_X_DGlab) | sin licencia | 1 |
| [mRally2/FramerateUnlocker](https://github.com/mRally2/FramerateUnlocker) | sin licencia | 1 |
| [mvrozanti/HyperHexagon](https://github.com/mvrozanti/HyperHexagon) | sin licencia | 1 |
| [nozwock/ce-cheat-tables](https://github.com/nozwock/ce-cheat-tables) | sin licencia | 1 |
| [olegyadrov/thefriendlyghost](https://github.com/olegyadrov/thefriendlyghost) | BSD-3-Clause | 1 |
| [olivia-mativi/shapez2-ct](https://github.com/olivia-mativi/shapez2-ct) | sin licencia | 1 |
| [olivia-mativi/tinyrogues-ct](https://github.com/olivia-mativi/tinyrogues-ct) | sin licencia | 1 |
| [pkmnya/mymspinyin](https://github.com/pkmnya/mymspinyin) | MIT | 1 |
| [polskiftw/cheatengine](https://github.com/polskiftw/cheatengine) | Apache-2.0 | 1 |
| [posio-dev/cheat-engine-scripts](https://github.com/posio-dev/cheat-engine-scripts) | Unlicense | 1 |
| [rqmaot/rqmaot.github.io](https://github.com/rqmaot/rqmaot.github.io) | sin licencia | 1 |
| [ruarq/Calturin](https://github.com/ruarq/Calturin) | MIT | 1 |
| [ryanbabij/mtwcameraunlock](https://github.com/ryanbabij/mtwcameraunlock) | sin licencia | 1 |
| [ryder7223/Minesweeper-Tools](https://github.com/ryder7223/Minesweeper-Tools) | sin licencia | 1 |
| [seyounff/Scripts_corekeeper](https://github.com/seyounff/Scripts_corekeeper) | sin licencia | 1 |
| [sheysyn/NFSU2.Clutch](https://github.com/sheysyn/NFSU2.Clutch) | MIT | 1 |
| [shui-dun/minitools](https://github.com/shui-dun/minitools) | MIT | 1 |
| [smolse/poc-or-gtfo](https://github.com/smolse/poc-or-gtfo) | sin licencia | 1 |
| [sourcehold/sourcehold-maps](https://github.com/sourcehold/sourcehold-maps) | GPL-3.0 | 1 |
| [synth-the-humanoid/KH1FM-Cheat-Table-EGS-1009](https://github.com/synth-the-humanoid/KH1FM-Cheat-Table-EGS-1009) | sin licencia | 1 |
| [timopomer/Apollo1.6](https://github.com/timopomer/Apollo1.6) | sin licencia | 1 |
| [trampi/x-rebirth-credit-export](https://github.com/trampi/x-rebirth-credit-export) | sin licencia | 1 |
| [trinityIV/crmsonD](https://github.com/trinityIV/crmsonD) | sin licencia | 1 |
| [ushineko/ag-scripts](https://github.com/ushineko/ag-scripts) | MIT | 1 |
| [vektorprime/shadow-of-war-save-editor](https://github.com/vektorprime/shadow-of-war-save-editor) | sin licencia | 1 |
| [vtorres/ravendawn-tools](https://github.com/vtorres/ravendawn-tools) | sin licencia | 1 |
| [X-Zero-L/dawn-atelier](https://github.com/X-Zero-L/dawn-atelier) | sin licencia | 1 |
| [xAranaktu/F1-Manager-2022-Cheat-Table](https://github.com/xAranaktu/F1-Manager-2022-Cheat-Table) | MIT | 1 |
| [zarroboogs/p4g-ct](https://github.com/zarroboogs/p4g-ct) | sin licencia | 1 |
| [ZeroSkill1/gh-pages](https://github.com/ZeroSkill1/gh-pages) | MIT | 1 |
| [zmrbak/PcWeChatHooK](https://github.com/zmrbak/PcWeChatHooK) | sin licencia | 1 |
| [zmrbak/SQLiteReverse](https://github.com/zmrbak/SQLiteReverse) | MIT | 1 |
| [zoomdbz/Cyberpunk-2077-Cheat-Engine-Cheat-tables](https://github.com/zoomdbz/Cyberpunk-2077-Cheat-Engine-Cheat-tables) | GPL-3.0 | 1 |
| [zzctrl/rxwg](https://github.com/zzctrl/rxwg) | sin licencia | 1 |
| [zzzzsky/CS1.6_Hook](https://github.com/zzzzsky/CS1.6_Hook) | sin licencia | 1 |
| [The-Grand-Archives/Dark-Souls-III-CT-TGA](https://github.com/The-Grand-Archives/Dark-Souls-III-CT-TGA) | sin licencia | 1 |
| [tox1cp4nd4/ce_cheat_tables](https://github.com/tox1cp4nd4/ce_cheat_tables) | sin licencia | 1 |
| [welstrec/ac-valhalla](https://github.com/welstrec/ac-valhalla) | sin licencia | 1 |
| [xtvaser/ramwatches](https://github.com/xtvaser/ramwatches) | MIT | 1 |
| [yuiastin/tcs-release-tools](https://github.com/yuiastin/tcs-release-tools) | sin licencia | 1 |
