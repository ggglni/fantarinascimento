# Fantarinascimento

Sito ufficiale della lega di fantacalcio **Fantarinascimento**, disponibile su [fantarinascimento.nl](https://fantarinascimento.nl).

## Pagine

| Pagina | Descrizione |
|--------|-------------|
| `index.html` | Homepage con hero e citazione di Boškov |
| `giocatori.html` | Schede dei manager della lega, con soprannome, anno e descrizione |
| `annali.html` | Indice delle stagioni, con una card per ogni annata |
| `annali-2026-2027.html` | Pagina di una stagione: foto, vincitori, partecipanti ed eventi |

## Struttura

```
fantarinascimento/
├── index.html
├── giocatori.html
├── annali.html
├── annali-2026-2027.html
├── style.css
├── CNAME
├── img/
│   ├── favicon.png
│   ├── logo-scudetto.png
│   ├── logo-champions.png
│   └── logo-coppa-italia.png
└── foto-aste/
    └── asta_2026.jpeg
```

## Come aggiornare i dati

Essendo un sito statico, tutti i dati si modificano direttamente nell'HTML:

- **Giocatori** — `giocatori.html`: nome, soprannome, anno e descrizione di ogni manager
- **Nuova stagione** — copia `annali-2026-2027.html`, rinominalo (es. `annali-2027-2028.html`) e aggiorna foto, vincitori, partecipanti ed eventi; aggiungi poi una card in `annali.html`
- **Vincitori di una stagione** — nella pagina della stagione, sezione *Vincitori*: sostituisci "TBD" con squadra/manager
- **Eventi di una stagione** — nella pagina della stagione, sezione *Eventi*: aggiungi una riga alla lista puntata
- **Foto delle aste** — cartella `foto-aste/`

## Deploy

Il sito è hostato su **GitHub Pages** con dominio custom configurato tramite DNS su Squarespace.
