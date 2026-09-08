# Calcolatore Giornate e Classifica

App web pubblica (PWA) per il Fantacalcio.

## Link dell'app

Dopo l'attivazione di GitHub Pages:

**https://niccologrillo1911-jpg.github.io/calcolatore-fantacalcio/**

Condividi questo link con chi deve usare l'app. Dal telefono: Apri il link → Aggiungi a Home.

## Come si aggiorna per tutti

1. Modifica i file nel repository (oppure chiedi a Grok di farlo).
2. Il commit su `main` pubblica in automatico la nuova versione.
3. Chi ha già aperto l'app deve chiuderla e riaprirla (con internet) per vedere le modifiche.

## Nota sui dati della classifica

I punteggi e le rose restano salvati nel browser di ogni telefono (`localStorage`).
Pubblicare l'app rende visibile a tutti la *stessa versione del programma*.
Se vuoi che anche i *dati* (giornate, voti, classifica) siano condivisi in tempo reale tra tutti, serve una sincronizzazione cloud: si può aggiungere.

## Attivare GitHub Pages (solo la prima volta)

Se il link non si apre ancora:

1. Apri https://github.com/niccologrillo1911-jpg/calcolatore-fantacalcio/settings/pages
2. In "Build and deployment" → Source scegli **GitHub Actions**
   (oppure Branch: `main` / folder: `/ (root)`)
3. Attendi 1-2 minuti e apri il link.
