# Fantarinascimento

Sito ufficiale della lega di fantacalcio **Fantarinascimento**, disponibile su [fantarinascimento.nl](https://fantarinascimento.nl).

## Pagine

| Pagina | Descrizione |
|--------|-------------|
| `index.html` | Homepage con hero e citazione di Boškov |
| `giocatori.html` | Schede dei 20 manager con nome squadra, anno e descrizione |
| `albo-doro.html` | Campioni in carica (Campionato, Champions League, Coppa Italia) e storico per stagione |
| `regolamento.html` | Regole della lega |

## Struttura

```
fantarinascimento/
├── index.html
├── giocatori.html
├── albo-doro.html
├── regolamento.html
├── style.css
├── favicon.svg
├── champions.svg
├── coppa-italia.svg
└── CNAME
```

## Come aggiornare i dati

Essendo un sito statico, tutti i dati si modificano direttamente nell'HTML:

- **Giocatori** — `giocatori.html`: nome, squadra, anno, descrizione di ogni manager
- **Campioni in carica** — `albo-doro.html`: sezione *Campione in Carica*, tre card per titolo
- **Storico stagioni** — `albo-doro.html`: tabella *Tutti i Campioni*, una riga per anno
- **Statistiche** — `albo-doro.html`: tabella *Statistiche Storiche*, titoli vinti per manager

## Deploy

Il sito è hostato su **GitHub Pages** con dominio custom configurato tramite DNS su Squarespace.
