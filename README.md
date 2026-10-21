# Studio ER

Editor di diagrammi Entità-Relazione che funziona nel browser, senza installare niente.

**Apri il sito:** https://thomas-addamo.github.io/studio-er/

## Cosa fa

- Entità ed entità deboli, relazioni e relazioni identificanti, generalizzazioni ISA, note
- Attributi chiave, chiave parziale, multivalore, derivati, composti, facoltativi
- Cardinalità `(min,max)` oppure `1 / N / M`, partecipazione totale, ruoli
- Verifica del modello (chiavi mancanti, cardinalità vuote, collegamenti errati)
- Traduzione nello schema logico relazionale e in SQL `CREATE TABLE`
- Salva e apri progetti in formato `.json` (anche trascinando il file sul foglio)
- Esporta il diagramma in PNG (1×–4×) o SVG, con sfondo bianco, scuro o trasparente
- Salvataggio automatico nel browser, annulla/ripeti, tema chiaro e scuro

## Scorciatoie

| Tasto | Azione |
| --- | --- |
| `V` `H` | Seleziona · sposta la vista |
| `E` `W` `R` `A` `G` `N` | Entità, entità debole, relazione, attributo, ISA, nota |
| `C` | Collega due elementi |
| Doppio clic | Rinomina (sul vuoto crea un'entità) |
| `Canc` | Elimina |
| `Ctrl Z` / `Ctrl Shift Z` | Annulla / ripeti |
| `Ctrl C` `Ctrl V` `Ctrl D` | Copia, incolla, duplica |
| `Ctrl S` / `Ctrl O` / `Ctrl E` | Salva, apri, esporta immagine |
| `F` | Adatta il diagramma alla finestra |

Tutto è in un solo file, `index.html`.
