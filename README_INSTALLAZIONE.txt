ONE MORE: RETRO SHIFT — PWA v2.23
==================================
Questa cartella contiene una web app installabile su iPhone; NON è un IPA.

PUBBLICAZIONE HTTPS (esempio GitHub Pages):
1. Crea un repository pubblico su GitHub.
2. Carica i file index.html, manifest.webmanifest, sw.js e la cartella icons, mantenendo i percorsi.
3. In Settings > Pages seleziona Deploy from a branch, branch main, cartella / (root).
4. Attendi la pubblicazione e apri l'URL HTTPS indicato da GitHub Pages.

INSTALLAZIONE SU IPHONE:
1. Apri il link HTTPS in Safari su iPhone.
2. Tocca Condividi > Aggiungi alla schermata Home > Aggiungi.
3. Avvia ONE MORE dall'icona aggiunta.
4. Apri il gioco una volta con connessione per preparare la cache offline; poi puoi giocare offline.

AGGIORNAMENTI:
Per la prossima versione sostituisci index.html e modifica il nome CACHE in sw.js.
La PWA installata scaricherà i nuovi file quando torna online; potrebbe essere necessario chiuderla e riaprirla.

SALVATAGGI:
I progressi sono memorizzati localmente sul dispositivo/browser tramite localStorage.
I salvataggi del file HTML aperto da Windows NON si trasferiscono automaticamente su iPhone.
Evita di cancellare i dati del sito o disinstallare la PWA senza un futuro sistema di esportazione.

NOTA: questa PWA non è stata pubblicata su un dominio HTTPS e non è stata collaudata fisicamente su iPhone.

SCHERMO INTERO:
- iPhone: la PWA avviata dall'icona Home usa la modalità standalone, senza barra di Safari.
- Chrome/Edge su Windows e Android: premi ⛶ SCHERMO INTERO nel menu.
- Safari iPhone non supporta normalmente requestFullscreen per una pagina HTML generica.
- Se hai già pubblicato v2.20, carica i nuovi file sovrascrivendo quelli vecchi, poi riapri la PWA.

v2.23: menu su iPhone esteso in altezza, senza intestazione di partita, pannello
a tutta larghezza e pulsanti adattivi. Lo schermo intero iOS dipende dall'avvio
dall'icona Home (PWA standalone); la barra di stato di iOS può rimanere visibile.
Aggiornare index.html e sw.js su GitHub Pages.

v2.23: corretto il menu iPhone ancorando pannello e comandi alla viewport visibile
e utilizzando la sua altezza reale; i pulsanti audio/impostazioni sono ora nel
flusso del layout, non più sovrapposti al bordo del pannello. Il pannello
riempie lo spazio verticale fino ai comandi inferiori.
