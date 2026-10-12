# 🔐 Prepara, scambia, verifica

> **Esercitazione interattiva (55 minuti) su dati e sicurezza nei prompt**, per il percorso formativo "L'intelligenza artificiale nella Pubblica Amministrazione".
> Sei fasi guidate per imparare a ridurre il contesto, costruire un prompt sicuro, revisionarsi a vicenda e documentare i controlli — su un caso **interamente fittizio**.

🔗 **Demo online:** [Prepara, scambia, verificahttps://gigicogo.github.io/Scheda-sicurezza-prompt/](https://gigicogo.github.io/Scheda-sicurezza-prompt/)

---

## 📋 Cos'è

Un singolo file HTML, senza backend né installazioni, che accompagna i partecipanti in un esercizio completo sul principio chiave della privacy by design: **minimizzare ciò che finisce in un prompt**. I gruppi lavorano su un caso fittizio (un utente con consumi anomali, in morosità, con contenzioso aperto), riducono il contesto, costruiscono il prompt, si scambiano il lavoro per una revisione incrociata e preparano una scheda finale documentata.

| Fase | Tempo | Cosa succede |
| --- | --- | --- |
| **1 · Triage del caso** | 7′ | Per ogni informazione del caso: serve al compito? Può far riconoscere la persona? Che azione proporre (rimuovi, sostituisci, generalizza, aggrega…) |
| **2 · Riduzione del contesto** | 10′ | Checklist di minimizzazione (8 voci obbligatorie) e scrittura del contesto ridotto |
| **3 · Costruzione del prompt** | 10′ | Campi guidati (output, destinatario, fonti, compito, tono, limiti) e anteprima assemblata in tempo reale |
| **4 · Revisione incrociata** | 10′ | Scambio di lavoro tra gruppi via JSON, rubrica di 8 domande, rilievi prioritari |
| **5 · Revisione finale e audit** | 13′ | Modifiche, verifiche completate e da completare, **audit a sorpresa** con estrazione casuale di una domanda |
| **6 · Preparazione restituzione** | 5′ | Tre decisioni di minimizzazione, due rilievi ricevuti, scheda finale generata automaticamente (stampa / PDF) |

## 🚀 Come si usa

1. Scarica `index.html` dal repo (o copialo da una chiavetta).
2. Aprilo con un doppio clic in qualunque browser moderno: **funziona anche offline**.
3. Proiettalo per la plenaria, oppure invialo ai piccoli gruppi perché lo usino sul proprio PC.

Per lo scambio tra gruppi non serve alcun server: il gruppo autore usa **"Esporta lavoro JSON"**, il gruppo revisore lo carica con **"Importa lavoro JSON"**, compila la rubrica e lo riesporta. Il timer integrato (55 minuti, con avanzamento per fase) è un supporto organizzativo: non blocca mai i campi.

## 🔒 Privacy e protezione dei dati

L'app è progettata per l'uso in un ente pubblico, quindi:

- **Nessun dato lascia il dispositivo.** Nessuna richiesta di rete, nessun invio a server o servizi di IA: il prompt costruito non viene mai spedito a un modello.
- **Caso interamente fittizio.** Un banner ricorda a ogni fase di non inserire dati personali reali, dati riservati o documenti dell'Ente.
- **Niente nominativi.** Il nome del gruppo è facoltativo e il campo lo dice esplicitamente.
- **Salvataggio solo locale** (localStorage del browser), con esportazione/importazione JSON validata campo per campo.
- **Scheda finale consapevole:** dichiara esplicitamente che l'elaborato documenta il lavoro svolto, ma non certifica l'anonimato, l'autorizzazione dello strumento o la conformità del prompt alle procedure dell'Ente.

## 🛠️ Struttura del repository

```text
├── index.html    # l'esercitazione completa (HTML + CSS + JS inline, zero dipendenze)
├── README.md     # questo file
```

Non serve build, npm, né alcuno strumento: solo un browser. Funziona su desktop, tablet e smartphone, con supporto a **dark mode** automatico, area sicura (notch) e stampa.

## 🌐 Pubblicazione gratuita (GitHub Pages)

1. Crea il repository e carica `index.html`.
2. Vai su **Settings → Pages**.
3. Sotto *Build and deployment*, seleziona il branch (`main`) e la cartella (`/root`), poi **Save**.
4. Dopo qualche minuto l'esercizio sarà online su `https://<tuo-username>.github.io/<repo>/`.

Netlify (free) è un'alternativa valida: trascina il file e ottieni un link immediato.

## 📐 Come è costruita l'esercitazione

L'app segue i contenuti del percorso sull'IA nella PA:

- **minimizzazione dei dati**: meno dati nel prompt, meno rischio (il filo conduttore di tutte le fasi);
- il messaggio chiave della giornata sulla privacy: **la pseudonimizzazione non è anonimizzazione** — un segnaposto come `[UTENTE_A]` non rende il caso anonimo se restano combinazioni identificative;
- la costruzione del prompt con **istruzioni di salvaguardia** (bozza, solo fonti fornite, niente invenzioni, revisione umana);
- la **revisione tra pari** e la **tracciabilità** come buone pratiche, prima che come obblighi.

## ✏️ Personalizzazione

Tutto il contenuto è in chiaro dentro `index.html`:

- **il caso fittizio e la finalità**: costanti `CASO`, `FIN` ed elenco `EL` (le informazioni da sottoporre a triage);
- **checklist e rubrica**: costanti `CHK` e `RUB`;
- **domande dell'audit**: costante `AUD` (l'estrazione evita automaticamente la ripetizione della stessa domanda);
- **tempi delle fasi**: costante `PH` (i minuti per fase; il totale si ricalcola automaticamente).

Se adatti l'esercizio al tuo ente, mantieni la regola d'ingaggio: solo casi fittizi, mai dati reali.

## 📄 Licenza

Aperta. E' possibile usare il file, cambiarlo, ottimizzarlo, correggerlo e usarlo in piena libertà senza obbligo di citare l'autore.

## 👤 Autore e contesto

**Gianluigi Cogo** — consulente e docente sui temi dell'IA generativa nella Pubblica Amministrazione.

L'app nasce come esercitazione del percorso operativo *"L'IA nella Pubblica Amministrazione — Percorso operativo per l'uso consapevole, sicuro e governato dell'IA generativa"* (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti), in particolare per le giornate su sicurezza/privacy e buone pratiche.

- 📮 Newsletter: [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 Blog: [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ YouTube: [youtube.com/@gigicogo](https://www.youtube.com/@gigicogo)
- 💼 LinkedIn: [linkedin.com/in/gigicogo](https://it.linkedin.com/in/gigicogo)
