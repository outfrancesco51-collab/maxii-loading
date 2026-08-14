
╔══════════════════════════════════════════════════════════════╗
║                      LOADING SCREEN                          ║
║                      BY MAXII STUDIO                         ║
╚══════════════════════════════════════════════════════════════╝


                    ITALIANO


📦 INSTALLAZIONE

1. Estrai la cartella della loading screen.

2. Inserisci la cartella:

   maxii_loading

   all'interno della cartella:

   resources/

3. Apri il file:

   server.cfg

4. Aggiungi questa riga:

   ensure maxii_loading

5. Riavvia il server.


📁 STRUTTURA DELLA RISORSA

maxii_loading/
│
├── fxmanifest.lua
├── index.html
├── music_yt.mp3
└── background.mp4


🖼️ LOGO PERSONALIZZATO

La loading screen include un logo personalizzabile.

Nella cartella della risorsa è presente il file:

logo.png

Per utilizzare il tuo logo, sostituisci semplicemente il file
esistente con la tua immagine.

IMPORTANTE:
Il nuovo file deve essere chiamato esattamente:

logo.png

Non modificare il nome del file, altrimenti il logo potrebbe
non essere visualizzato correttamente nella loading screen.


🎵 SISTEMA MUSICALE

La loading screen include un sistema audio integrato e completamente
gestibile direttamente dalla schermata di caricamento.

▶ PLAY
Avvia la musica.

Ⅱ PAUSA
Mette in pausa la musica senza chiudere la loading screen.

🔊 VOLUME
Lo slider permette di regolare il volume della musica dal:

0% ─────────────── 100%

Il volume iniziale è impostato al:

22%


⚠️ AUTOPLAY

In alcuni casi FiveM o il browser NUI possono impedire l'avvio
automatico dell'audio.

Se la musica non parte automaticamente:

→ clicca una volta sulla loading screen

La musica verrà avviata immediatamente.


🎬 SFONDO PERSONALIZZATO

La loading screen supporta uno sfondo video personalizzato.

Per utilizzare un tuo video, inserisci:

background.mp4

nella cartella della risorsa.

Il video verrà caricato automaticamente come sfondo della loading screen.

IMPORTANTE:
Il file deve essere chiamato esattamente:

background.mp4


🎵 MUSICA PERSONALIZZATA

Puoi sostituire la musica inclusa con una tua traccia.

Inserisci il file:

music_yt.mp3

nella cartella della risorsa.

Il file verrà utilizzato automaticamente dalla loading screen.

IMPORTANTE:
Il file deve essere chiamato esattamente:

music_yt.mp3


📊 SISTEMA DI PROGRESSO

La barra di caricamento è progettata per funzionare con gli eventi
di caricamento di FiveM.

La loading screen ascolta l'evento:

loadProgress

e aggiorna automaticamente la percentuale di caricamento quando
riceve gli aggiornamenti dal client.

È inoltre presente un sistema di fallback visivo che mantiene
l'animazione della barra anche quando il client non invia
immediatamente gli aggiornamenti.

Questo permette di evitare una barra bloccata allo 0% durante
le prime fasi del caricamento.


⚙️ CONFIGURAZIONE

La loading screen è stata progettata per essere semplice da installare
e utilizzare.

Non sono richieste configurazioni complesse.

Per personalizzare:

• Logo
• Testi
• Colori
• Musica
• Video di sfondo
• Suggerimenti
• Link Discord

è sufficiente modificare i relativi elementi presenti nel file:

index.html


🖥️ REQUISITI

• FiveM
• NUI abilitata
• Resource FiveM funzionante
• fxmanifest.lua configurato correttamente


❗ NOTE IMPORTANTI

• Non rinominare music_yt.mp3 se non modifichi anche il riferimento
  all'interno di index.html.

• Non rinominare background.mp4 se non modifichi anche il riferimento
  all'interno di index.html.

• Assicurati che la risorsa venga avviata prima di entrare nel server.

• Dopo qualsiasi modifica alla risorsa, riavvia FiveM/server per
  applicare correttamente i cambiamenti.


🚀 INSTALLAZIONE RAPIDA

resources/
└── maxii_loading/
    ├── fxmanifest.lua
    ├── index.html
    ├── music_yt.mp3
    └── background.mp4


server.cfg:

ensure maxii_loading


──────────────────────────────────────────────────────────────

          LOADING SCREEN
Designed & Developed by MAXII STUDIO

Una loading screen moderna e ottimizzata per server FiveM,
con supporto per video di sfondo, musica personalizzata,
controllo volume e sistema di caricamento dinamico.

──────────────────────────────────────────────────────────────



                    ENGLISH


📦 INSTALLATION

1. Extract the loading screen folder.

2. Place the folder:

   maxii_loading

   inside:

   resources/

3. Open the file:

   server.cfg

4. Add the following line:

   ensure maxii_loading

5. Restart your server.


📁 RESOURCE STRUCTURE

maxii_loading/
│
├── fxmanifest.lua
├── index.html
├── music_yt.mp3
└── background.mp4


🖼️ CUSTOM LOGO

The loading screen includes a customizable logo.

Inside the resource folder, you will find the file:

logo.png

To use your own logo, simply replace the existing file with
your own image.

IMPORTANT:
The new file must be named exactly:

logo.png

Do not change the file name, otherwise the logo may not be
displayed correctly on the loading screen.


🎵 MUSIC SYSTEM

The loading screen includes an integrated audio system that can be
fully controlled directly from the loading screen.

▶ PLAY
Starts the music.

Ⅱ PAUSE
Pauses the music without closing the loading screen.

🔊 VOLUME
The volume slider allows you to adjust the music volume from:

0% ─────────────── 100%

The default volume is set to:

22%


⚠️ AUTOPLAY

In some cases, FiveM or the NUI browser may prevent the audio
from starting automatically.

If the music does not start automatically:

→ click once on the loading screen

The music will start immediately.


🎬 CUSTOM BACKGROUND

The loading screen supports a custom video background.

To use your own video, place:

background.mp4

inside the resource folder.

The video will automatically be loaded as the loading screen background.

IMPORTANT:
The file must be named exactly:

background.mp4


🎵 CUSTOM MUSIC

You can replace the included music with your own track.

Place the file:

music_yt.mp3

inside the resource folder.

The file will automatically be used by the loading screen.

IMPORTANT:
The file must be named exactly:

music_yt.mp3


📊 PROGRESS SYSTEM

The loading bar is designed to work with FiveM loading events.

The loading screen listens for the event:

loadProgress

and automatically updates the loading percentage when it receives
updates from the client.

A visual fallback system is also included to keep the progress bar
animated when the client does not immediately send updates.

This prevents the progress bar from remaining stuck at 0% during
the early stages of the loading process.


⚙️ CONFIGURATION

The loading screen was designed to be simple to install and use.

No complex configuration is required.

You can customize:

• Logo
• Text
• Colors
• Music
• Background video
• Tips
• Discord link

by editing the corresponding elements inside:

index.html


🖥️ REQUIREMENTS

• FiveM
• NUI enabled
• Working FiveM resource
• Correctly configured fxmanifest.lua


❗ IMPORTANT NOTES

• Do not rename music_yt.mp3 unless you also change its reference
  inside index.html.

• Do not rename background.mp4 unless you also change its reference
  inside index.html.

• Make sure the resource is started before joining the server.

• After making any changes to the resource, restart FiveM/server
  to properly apply the changes.


🚀 QUICK INSTALLATION

resources/
└── maxii_loading/
    ├── fxmanifest.lua
    ├── index.html
    ├── music_yt.mp3
    └── background.mp4


server.cfg:

ensure maxii_loading


──────────────────────────────────────────────────────────────

          LOADING SCREEN
Designed & Developed by MAXII STUDIO

A modern and optimized loading screen for FiveM servers,
featuring background video support, custom music,
volume control and a dynamic loading system.

──────────────────────────────────────────────────────────────

