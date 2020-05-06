# Useful Scripts on Ubuntu/Debian for Minecraft Servers
**English/Italian** Guide.

_**English Guide**_

Thanks to these scripts you can **always keep** your **Minecraft Server** running on your system and you can access the console when you need it. The package includes three simple executable scripts on **Ubuntu/Debian** systems: start.sh, startserver.sh, console.sh

* **start.sh** - Create a "screen", which is an always active background process.

* **startserver.sh** - Process that will start your Minecraft Server on the created screen.

* **console.sh** - Script to access the Minecraft Server console, where you can read the logs and run commands.

_**How to install**_

Firstly let's install "**screen**" package on our **Ubuntu/Debian** system with:

`sudo apt update && apt-get -y install screen`
Download these script from GitHub, then upload to your Minecraft Server directory, next launch these commands in SSH root.

* `chmod 777 start.sh`
* `chmod 777 startserver.sh`
* `chmod 777 console.sh`

Next, rename the _.jar_ file of your **Minecraft Server** to "_server.jar_".

_**How to open script**_

To open this script and so your Minecraft Server, type in directory with SSH terminal: `./start.sh`
Then, access to console typing this in SSH root: `./console`

_Enjoy!_

***

_**Guida Italiana**_

Grazie a questi script potrai tenere **sempre acceso** il tuo **Server Minecraft** sulla tua macchina e potrai accedere alla console quando avrai bisogno. Il pacchetto comprende tre semplici script eseguibili sui sistemi **Ubuntu/Debian**: start.sh, startserver.sh, console.sh

* start.sh - Crea uno "screen", ossia un processo in background sempre attivo.

* startserver.sh - Processo che avvierà il tuo Server Minecraft nello screen creato.

* console.sh - Script per accedere alla console del Server Minecraft, dove potrai leggere i log ed eseguire comandi.

_**Come installare**_

Innanzitutto installiamo il package "**screen**" sul nostro sistema operativo **Ubuntu/Debian** eseguendo il comando in terminale SSH da root:

`sudo apt update && apt-get -y install screen`
Scarica i seguenti script da questa pagina GitHub, successivamente caricali nella cartella del tuo Minecraft Server, infine esegui i seguenti comandi in SSH da root.

* `chmod 777 start.sh`
* `chmod 777 startserver.sh`
* `chmod 777 console.sh`

Come ultima cosa, rinomina il file _.jar_ del tuo **Minecraft Server** in "_server.jar_".

_**Come aprire lo script**_

Per aprire lo script e quindi anche il vostro Server Minecraft, digita sul terminale SSH con utente root nella cartella dove li avete caricati, il comando `./start.sh`
Infine, per accedere alla console ti basterà digitare in SSH con utente root: `./console`

_Good Game!_
