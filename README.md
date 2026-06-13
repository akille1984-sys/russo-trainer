# Russo Trainer

Web app autonoma per esercitarsi con il vocabolario russo insieme a una persona che non legge il cirillico.

## Funzioni presenti nella versione 0.1

- vocabolario modificabile dal browser;
- pronuncia guidata per italofoni;
- domande russo → italiano e italiano → russo;
- sessioni da 30, 40 o 50 domande;
- valutazione: corretta, quasi corretta, errata;
- ripetizione adattiva basata sugli errori;
- statistiche essenziali;
- esportazione e importazione dei dati in JSON;
- funzionamento offline tramite service worker;
- installazione come PWA quando supportata dal browser.

## Pubblicazione con GitHub Pages

Aprire **Settings → Pages** nella repository e scegliere:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/ (root)**

Dopo il salvataggio, il sito sarà disponibile all'indirizzo indicato da GitHub Pages.

## Dati

Il vocabolario e le statistiche sono conservati nel `localStorage` del browser. Usare regolarmente **Esporta backup** per creare una copia trasferibile.
