<!-- ELUCENIA technical documentation · escala-de-lawton · it · no clinical/professional/rights approval -->

# Scala di Lawton-Brody (IADL)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-de-lawton)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Telefono

`tel`

- `a` — Usa il telefono di propria iniziativa (cerca e compone i numeri)
- `b` — Compone alcuni numeri conosciuti
- `c` — Risponde, ma non compone numeri
- `d` — Non usa il telefono

### Acquisti

`compras`

- `a` — Fa tutti gli acquisti autonomamente
- `b` — Fa autonomamente solo piccoli acquisti
- `c` — Ha bisogno di essere accompagnato per qualsiasi acquisto
- `d` — Non è in grado di fare acquisti

### Preparazione dei pasti

`comida`

- `a` — Pianifica, prepara e serve pasti adeguati autonomamente
- `b` — Prepara i pasti se riceve gli ingredienti
- `c` — Riscalda e serve pasti pronti, ma senza una dieta adeguata
- `d` — Ha bisogno che altri preparino e servano i pasti

### Faccende domestiche

`casa`

- `a` — Si occupa della casa autonomamente o con aiuto occasionale nei lavori pesanti
- `b` — Svolge lavori leggeri (lavare i piatti, rifare il letto)
- `c` — Svolge lavori leggeri, ma non mantiene una pulizia adeguata
- `d` — Ha bisogno di aiuto in tutte le attività
- `e` — Non svolge alcuna attività domestica

### Lavare la biancheria

`roupa`

- `a` — Lava tutti i propri indumenti
- `b` — Lava piccoli indumenti
- `c` — Tutta la biancheria viene lavata da altri

### Trasporto

`transp`

- `a` — Usa i mezzi pubblici o guida autonomamente
- `b` — Prende da solo un taxi o un servizio tramite app, ma non usa i trasporti pubblici
- `c` — Usa i mezzi pubblici se accompagnato
- `d` — Si sposta solo in taxi o in auto con l’aiuto di un’altra persona
- `e` — Non esce di casa

### Farmaci

`remedio`

- `a` — Assume i farmaci autonomamente alla dose e all’orario corretti
- `b` — Assume i farmaci se qualcuno prepara prima le dosi
- `c` — Non è in grado di assumere i farmaci autonomamente

### Finanze

`dinheiro`

- `a` — Gestisce le finanze da solo
- `b` — Fa acquisti quotidiani, ma ha bisogno di aiuto per operazioni bancarie e acquisti importanti
- `c` — Non è in grado di gestire il denaro

## Edizione del metodo

Lawton–Brody 1969: adattamento locale 8 domini 0–1, totale 0–8 per entrambi i sessi; non la versione originale specifica per sesso

## Formula documentata

Ogni attività vale 1 (indipendente) o 0 (dipendente) secondo il livello:

Telefono: 1 nei primi tre.

Acquisti e pasti: 1 solo nel primo.

Casa: 1 tranne “non partecipa”.

Bucato: 1 nei primi due.

Trasporto: 1 nei primi tre.

Farmaci: 1 solo nel primo.

Finanze: 1 nei primi due.

Totale 0 (dipendente) a 8 (indipendente).

## Limiti e popolazione

Questa versione di Lawton valuta otto attività strumentali e usa un totale da 0 a 8 per tutti i generi, secondo le indicazioni HIGN del 2019; non applica il precedente punteggio maschile a cinque item. Le indicazioni consultate non raccomandano lo strumento per gli anziani istituzionalizzati. Le risposte della persona o di un informatore descrivono la funzione percepita e non dimostrano l’esecuzione reale di ciascun compito; possono sovrastimare o sottostimare la capacità e non rilevare piccoli cambiamenti. Registrare chi ha risposto e il contesto della valutazione.

## Riferimenti

- [Lawton MP, Brody EM. Assessment of older people: self-maintaining and instrumental activities of daily living. Gerontologist, 1969.](https://doi.org/10.1093/geront/9.3_Part_1.179)

- [HIGN,TryThis23,revised2019](https://hign.org/sites/default/files/2020-06/Try_This_General_Assessment_23.pdf)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

Indipendente nelle attività strumentali


### 2

Dipendenza in 3 attività: acquisti, farmaci, finanze


### 3

Dipendenza in 6 attività: acquisti, preparazione dei pasti, faccende domestiche, bucato, trasporto, farmaci

