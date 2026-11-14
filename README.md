# Prepara, scambia, verifica — versione individuale

Web app didattica autonoma per il modulo **Dati e sicurezza nei prompt** del percorso di formazione sull'intelligenza artificiale nella Pubblica Amministrazione.

Questa è la versione per **aula virtuale con partecipanti individuali**, adattata dal laboratorio originario organizzato in gruppi. **Durata prevista: 40 minuti.**

## Come funziona

1. Apri `index.html` con un browser recente, o pubblicalo su GitHub Pages.
2. Premi **Avvia esercitazione individuale**. Il timer è facoltativo: si avvia con **Avvia / riprendi**.
3. Lavora sul **solo caso fittizio**, senza inserire dati reali.
4. Nella fase 4 cambia prospettiva: da autore del prompt diventi **revisore del tuo stesso lavoro**. Compila la rubrica e valuta quattro osservazioni di un **revisore simulato**. Alcune sono intenzionalmente fuorvianti. Dopo averle motivate tutte, premi **Confronta le mie decisioni con la guida**.
5. Correggi il prompt, completa l'audit e scarica la scheda finale usando **Stampa / salva PDF**. Se vuoi conservare una copia modificabile, usa **Esporta lavoro JSON**.

**«Scambia» non significa più scambiare file con altri partecipanti: significa scambiare il punto di vista, passando da autore a revisore.**

## Le sei fasi

| Fase | Attività | Durata |
| --- | --- | ---: |
| 1 | Triage del caso fittizio | 7 min |
| 2 | Riduzione del contesto e checklist | 7 min |
| 3 | Costruzione del prompt | 8 min |
| 4 | Scambio di prospettiva: autoverifica e revisore simulato | 8 min |
| 5 | Revisione finale e audit | 7 min |
| 6 | Restituzione individuale | 3 min |
| **Totale** | | **40 min** |

Il timer è indicativo; non blocca i campi. Le etichette delle fasi indicano la completezza, **non un voto né una certificazione**.

## Backup, salvataggio, privacy

- L'app non richiede credenziali, non chiama servizi di IA, non usa analisi del traffico e non trasmette i testi a server. Funziona anche offline.
- Dove disponibile, il lavoro è salvato automaticamente con `localStorage` nel browser e sul dispositivo usato.
- **Esporta lavoro JSON / Importa lavoro JSON** servono soltanto per il **proprio backup** o per riprendere il proprio lavoro su un altro dispositivo. Non si inviano file tra partecipanti.
- Per consegnare un riepilogo leggibile, usa **Stampa / salva PDF**.
- Non inserire dati personali reali, documenti dell'Ente o contenuti riservati. Gli esempi sono interamente fittizi.
- Le quattro osservazioni del revisore sono **testi didattici statici**, non output di un modello IA.
- La scheda finale documenta scelte compiute nell'esercitazione: **non certifica** anonimizzazione, autorizzazioni dell'Ente, conformità privacy né correttezza della bozza.

## Pubblicazione su GitHub Pages

Per aggiornare il repository esistente `gigicogo/Scheda-sicurezza-prompt`:

1. Conserva una copia del vecchio `index.html` **fuori dalla cartella pubblicata**, o su un branch di backup.
2. Sostituisci nella root del repository l'`index.html` con il nuovo file.
3. Sostituisci o aggiorna `README.md`.
4. Se non è già attivo, abilita **Settings → Pages → Deploy from a branch → main → /(root)**.
5. Apri il link GitHub Pages del repository e controlla la versione visualizzata. In caso di cache, prova una finestra privata o un aggiornamento forzato.

Nessun build step, server, pacchetto npm o servizio esterno necessario.

## Che cosa cambia rispetto alla versione originaria

- Timer e regia **da 55 a 40 minuti**.
- Nessuna formazione di gruppi o importazione di elaborati altrui.
- Fase 4: rubrica di 8 controlli **mantenuta**; aggiunti 4 pareri predefiniti, scelta motivata e guida di confronto.
- Restituzione e PDF adattati al singolo partecipante.
- Backup JSON identificato come **formato individuale v2**, distinto da quello originario.
- Grafica, navigazione, salvataggio locale, prompt modificabile e audit a sorpresa mantenuti.

### Riservatezza delle soluzioni

La guida del formatore è distribuita separatamente come `GUIDA_FORMATORE.md`: **non va caricata nel repository pubblico**.

## Contesto del progetto

L'app nasce come esercitazione nel percorso operativo *"L'IA nella Pubblica Amministrazione — Percorso operativo per l'uso consapevole, sicuro e governato dell'IA generativa"* (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti).

---

## 📄 Licenza e riuso

Puoi usare, copiare, modificare e condividere questo progetto, anche per attività formative, professionali e commerciali, senza chiedere un’autorizzazione preventiva.

Salvo diversa indicazione, il codice è distribuito con licenza [MIT](https://opensource.org/license/mit), mentre i testi e i materiali didattici sono distribuiti con licenza [Creative Commons Attribuzione 4.0 Internazionale](https://creativecommons.org/licenses/by/4.0/deed.it).

Nel riuso, conserva gli avvisi previsti dalla licenza MIT; per testi e materiali didattici, cita **Gianluigi Cogo**, inserisci un collegamento al progetto originale e alla licenza e indica eventuali modifiche. Gli eventuali materiali di terzi mantengono le rispettive licenze.

## 👤 Autore e contesto

**Gianluigi Cogo** — Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa, dell’innovazione e della comunicazione.

- 📮 Newsletter: [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 Blog: [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ YouTube: [youtube.com/@gigicogo](https://www.youtube.com/@gigicogo)
- 💼 LinkedIn: [linkedin.com/in/gigicogo](https://it.linkedin.com/in/gigicogo)
