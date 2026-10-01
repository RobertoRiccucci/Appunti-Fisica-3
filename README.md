# Appunti di Fisica 3

Appunti del corso di **Fisica 3** tenuto dal prof. Giovanni Signorelli all'Università di Pisa, scritti in LaTeX.
Il contenuto segue il programma svolto nell'anno accademico 2026/2027, per cui non è garantito che rimanga valido anche per gli anni successivi.

L'obiettivo è raccogliere in un unico testo tutto il programma dell'anno, in una forma ordinata e compatta che permetta di preparare l'esame senza dover ricorrere a materiale sparso.

## Dove trovare il PDF

Il PDF compilato si trova in:

**[`build/Fisica_3.pdf`](build/Fisica_3.pdf)**

Viene aggiornato man mano che vengono aggiunte nuove lezioni ed esercitazioni.

## Contenuti

Gli appunti sono divisi in due parti.

### Teoria

| Capitolo | Argomenti |
|---|---|
| 1. Decadimenti | Decadimento radioattivo, catene di decadimento, tipi di decadimenti, radioattività naturale |

### Esercitazioni

Negli appunti non sono presenti esercizi svolti a parte, ma sono riportate tutte le esercitazioni tenute durante l'anno dalla prof.ssa Giulia Casarosa.

| Esercitazione | Argomenti |
|---|---|
| I. Datazione | Datazione con U–Pb, datazione con ¹⁴C |
| II. Energia nei decadimenti | Decadimento a 2 corpi, decadimento a 3 corpi |

> Il lavoro è in corso: nuovi capitoli verranno aggiunti durante l'anno.

## Struttura della repository

```
Appunti_Fisica_3/
├── Fisica_3.tex          # File principale: frontespizio, indice e inclusione dei capitoli
├── chapters/
│   ├── template.tex      # Preambolo: pacchetti, stile e comandi personalizzati
│   ├── preface.tex       # Prefazione
│   ├── capitolo_N.tex    # Capitoli di teoria
│   └── esercitazione_N.tex  # Esercitazioni
├── foto/                 # Immagini e figure usate nel testo
├── build/
│   └── Fisica_3.pdf      # PDF compilato
└── .vscode/              # Impostazioni e snippet LaTeX per VS Code
```

## Compilazione

Per compilare il documento in locale serve una distribuzione LaTeX (ad esempio TeX Live o MacTeX). Dalla cartella principale:

```bash
latexmk -pdf -outdir=build Fisica_3.tex
```

In alternativa, con VS Code e l'estensione LaTeX Workshop, il file radice `Fisica_3.tex` è già impostato in `.vscode/settings.json`.

## Contatti

Per segnalare errori o suggerire correzioni puoi aprire una *issue* su GitHub oppure scrivere a robertoriccucci1304@gmail.com.