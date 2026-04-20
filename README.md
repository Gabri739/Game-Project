# Simon: The Imprisoned

[![Unreal Engine](https://img.shields.io/badge/Unreal_Engine_5.4-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)](https://www.unrealengine.com/)
[![Blueprints](https://img.shields.io/badge/Blueprints-Visual_Scripting-2C73D2?style=for-the-badge)](#)
[![Game Development](https://img.shields.io/badge/Game_Development-FF6C37?style=for-the-badge)](#)

Questo progetto è un videogioco d'azione sviluppato interamente in **Unreal Engine 5.4**. L'obiettivo del progetto è stato quello di implementare da zero tutte le meccaniche core che costituiscono un gioco moderno, dalla gestione del movimento del giocatore fino alla creazione di incontri complessi contro i boss.

---

## 🚀 Meccaniche di Gioco e Funzionalità (Core Loops)

Il progetto esplora e implementa i seguenti sistemi fondamentali del Game Development:

* **🏃‍♂️ Movement System:** Sistema di locomozione fluido che risponde in modo reattivo agli input del giocatore, sfruttando l'anim graph di Unreal.
* **⚔️ Combat System:** Sistema di combattimento dinamico con gestione di hitbox, combo, parate e danni.
* **👹 Boss Fight:** Progettazione di uno scontro epico con un boss, dotato di pattern d'attacco multipli e transizioni di fase in base alla salute rimanente.
* **📜 Storyline & Quest:** Integrazione di elementi narrativi per guidare il giocatore attraverso l'esperienza di gioco.
* **🗺️ Level Design & Environment:** Creazione di una mappa esplorabile curata nel dettaglio, posizionamento strategico di nemici e ostacoli.
* **🎵 Audio Design:** Implementazione di Sound Cues per passi, impatti delle armi e colonna sonora dinamica che si adatta all'azione (es. musica di transizione durante la boss fight).
* **⚙️ Sistema di Impostazioni (Settings):** Menu UI completo per la regolazione grafica, del volume e della sensibilità dei controlli.

---

## 🛠️ Stack Tecnologico e Architettura

Tutta la logica di backend e le meccaniche di gameplay sono state sviluppate utilizzando il sistema di **Visual Scripting (Blueprints)** nativo di Unreal Engine. Questo ha permesso una rapida iterazione e un testing immediato delle meccaniche.

* **Game Engine:** Unreal Engine 5.4
* **Programmazione:** Blueprints (Object-Oriented Visual Scripting)
* **Assets & Props:** Modelli 3D, animazioni e texture integrati tramite [FAB](https://www.fab.com/) e l'Unreal Engine Marketplace.
