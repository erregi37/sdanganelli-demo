# Sdanganelli & Associati — demo editoriale

Prototipo **navigabile e responsive** per mostrare un possibile restyling del sito giuridico Sdanganelli & Associati.

## Demo

https://erregi37.github.io/sdanganelli-demo/

- Homepage editoriale con 6 pubblicazioni realmente presenti sul sito ufficiale.
- Ricerca istantanea e filtri per materia.
- **Pagine articolo dedicate** tramite `articolo.html?slug=...` (nessun popup).
- Indice dell'articolo, massima, sintesi strutturata, informazioni del provvedimento, contenuti correlati, copia collegamento.
- Visualizzatore PDF in pagina ove disponibile, collegato al documento originale pubblicato dallo studio.
- Navigazione desktop/mobile e link alle fonti.

## File

- `index.html`: homepage e ricerca
- `articolo.html`: template di lettura
- `articles.js`: dati dei sei articoli con link all'originale e ai PDF
- `styles.css`: design responsive

## Limiti della demo

I **titoli, i riferimenti, le fonti e i PDF** derivano da pubblicazioni vere; il corpo dei testi nell'ambiente di prova è una **sintesi redazionale**, non una copia integrale degli approfondimenti originali. I documenti PDF sono caricati dal sito originale; se il browser ne impedisce la visualizzazione incorporata, si può aprirli con il pulsante dedicato. Il caricamento delle foto stock avviene da Pexels.

Per il sito definitivo serviranno inventario e backup, migrazione dell'archivio originale, conservazione degli URL, corretta gestione dei diritti sulle immagini e integrazione con un CMS per la pubblicazione di nuovi articoli.

**Il sito originale sdanganelli.it non viene modificato.**
