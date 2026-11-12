# Sistemi, in pratica

Percorso interattivo in italiano per studenti delle scuole superiori: sistemi operativi, storia di Windows e Linux, differenze, virtualizzazione e laboratorio Oracle VirtualBox. Undici lezioni, per circa nove ore e 45 minuti di didattica, con BIOS/UEFI, supporti CD/DVD e USB avviabili, installazioni guidate di Ubuntu e Windows, quiz spiegati, cronologia, simulatori, esercizi, scheda stampabile e criteri di valutazione.

Sito: https://gianlucagenova-cyber.github.io/sistemi-in-pratica/

## Aprire il sito

Aprire `docs/index.html` in un browser moderno. Non servono installazione di librerie, compilazione, account studenti o un server applicativo. Per la pubblicazione GitHub Pages usare il branch principale e la cartella `/docs`.

## Ambiente del laboratorio

Mini PC Windows 11, Intel i7, 16 GB RAM, SSD 500 GB, VirtualBox già installato. Verificare lo spazio effettivamente libero. Eseguire una sola VM per volta, soprattutto passando tra Ubuntu e Windows. Per Windows guest utilizzare le licenze scolastiche adatte all’uso in VM.

## Modificare

- `docs/content.js`: lezioni, quiz, cronologia e passaggi guidati.
- `docs/app.js`: navigazione, simulatori e salvataggio locale.
- `docs/advanced.js`: percorso di nove ore, guida Windows, esercizi e verifica.
- `docs/boot.js`: BIOS/UEFI, supporti di installazione e simulazione di avvio.
- `docs/brands.js`: loghi pertinenti alle lezioni e attribuzioni.
- `docs/style.css`: impaginazione responsive.

I progressi sono memorizzati nel browser e non inviati a un docente o a un server. Sono separati per dispositivo e origine del sito: passare dalla copia locale a GitHub Pages non trasferisce i progressi. Su PC condivisi azzerarli prima di iniziare un nuovo percorso. Non raccoglie nomi, password o credenziali.

I PDF della cartella originale `materiale` non sono inclusi nel repository pubblico. I riferimenti ufficiali sono riportati nella lezione finale. Le indicazioni sono didattiche: consultare i requisiti della specifica versione di sistema e hypervisor prima dell’installazione.
