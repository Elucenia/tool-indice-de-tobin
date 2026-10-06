<!-- ELUCENIA technical documentation · indice-de-tobin · it · no clinical/professional/rights approval -->

# Indice di Tobin (respirazione rapida e superficiale)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/indice-de-tobin)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Frequenza respiratoria spontanea

`fr`

atti/min · intervallo: 1–80

### Volume corrente spontaneo

`vt`

mL · intervallo: 50–1500

## Edizione del metodo

RSBI/Yang–Tobin 1991: f/VT, VT in litri; non confondere con mL

## Formula documentata

f/VT = frequenza respiratoria (atti/min) ÷ volume corrente (litri).

## Limiti e popolazione

L’RSBI è stato studiato come predittore dell’esito dei tentativi di svezzamento dalla ventilazione. Il risultato dipende dalle condizioni e dalla tecnica di misurazione e da solo non conferma la capacità di proteggere le vie aeree o la sicurezza dell’estubazione. Un indice favorevole non equivale a un successo garantito.

## Riferimenti

- [Yang KL, Tobin MJ. A prospective study of indexes predicting the outcome of trials of weaning from mechanical ventilation. N Engl J Med, 1991.](https://doi.org/10.1056/NEJM199105233242101)

- [Boles JM et al. Weaning from mechanical ventilation. Eur Respir J, 2007.](https://doi.org/10.1183/09031936.00010206)

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

Sotto 105: favorisce il successo dello svezzamento


### 2

105 o più: predice fallimento dello svezzamento


### 3

105 o più: predice fallimento dello svezzamento

