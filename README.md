# Sdanganelli & Associati — demo di rinnovo del sito

**Repository:** erregi37/sdanganelli-demo

**Demo:** https://erregi37.github.io/sdanganelli-demo/

## Documento guida

La struttura e le scelte progettuali seguono il documento consegnato dallo Studio: **MASTER PLAN – RINNOVO SITO WEB STUDIO LEGALE**.

### Obiettivo principale

Sito istituzionale per privati e aziende in tutta Italia: richieste di contatto, specializzazioni, presentazione dello Studio e dei professionisti. La pubblicazione delle sentenze resta un'attività fondamentale, ma non sostituisce le pagine di presentazione e contatto.

### Sitemap dimostrativa

- Home (`index.html`)
- Lo studio (`pagina.html?sezione=studio`)
- Gli avvocati (`pagina.html?sezione=avvocati`)
- Aree di specializzazione (`pagina.html?sezione=aree`)
- Schede delle singole specializzazioni (`pagina.html?sezione=area&slug=...`)
- Sentenze e vittorie dello Studio (`pagina.html?sezione=casi`)
- Massime e note a sentenza (`pagina.html?sezione=pubblicazioni`)
- Pagine articolo (`articolo.html?slug=...`)
- Contatti / appuntamenti (`pagina.html?sezione=contatti`)
- Segnaposto per versione inglese, Privacy e Cookie Policy

## Stato delle funzionalità

**Funzionante in questa demo:** navigazione e mobile menu, schede materie, ricerca e filtri nella sezione pubblicazioni, pagine articolo, PDF originali tramite collegamenti, link email.

**Non ancora operative, solo dimostrate:** invio del form di contatto (nessun dato viene inviato), calendario appuntamenti, WhatsApp (numero da confermare), versione inglese integrale, Analytics 4, informativa privacy/cookie definitiva, backend CMS. Non si inventano vittorie, ruoli o profili professionali.

## Vincoli di hosting e migrazione

Il sito di produzione è su **Aruba**, con **WordPress 4.x** (versione esatta da verificare). Aruba gestisce inoltre dominio e servizi di posta/PEC. Nessuna modifica al DNS, alla posta, alla PEC, al dominio o al sito WordPress va effettuata nel corso della demo.

Passaggi previsti prima del lancio:

1. Ricognizione di WordPress, versione PHP/MySQL, tema, plugin, database e hosting.
2. Backup verificato di **file + database** e inventario di articoli, autori, date, allegati PDF, categorie e permalink.
3. Nuova installazione WordPress aggiornata in ambiente di **staging separato**, senza aggiornare direttamente WordPress 4.x in produzione.
4. Creazione del tema e migrazione dell'intero archivio conservando i vecchi URL, ove possibile; redirect 301 per eventuali URL mutati.
5. Test di accessibilità, responsive, form email, spam protection, eventuale calendario/WhatsApp, SEO, analytics e sicurezza.
6. Messa online concordata dopo verifica completa e con piano di rollback. Verificare la configurazione di DNS, MX, SPF, DKIM e DMARC prima di qualunque cambiamento infrastrutturale; mantenere la posta e PEC inalterate se non richiesto.
7. Consegna di credenziali, file, manuale d'uso, formazione e garanzia post-lancio da concordare secondo il masterplan.

## Reference citate nel masterplan

- birdmarella.com — essenzialità, homepage compatta, **senza** video di sfondo
- studiolegalestefanelli.it — semplicità istituzionale, chiarezza, lingua inglese
- studiolegalegiaquinto.it — CTA al contatto e FAQ
- studiobclaw.it — schede avvocati, presentazione casi, CTA consulenza

Da evitare: scrolling lunghissimo, parallax, animazioni vistose e una sezione News generica.
