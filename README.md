# Privacy Policy — Diggio Agent IA

> Ultimo aggiornamento: 16 aprile 2026

---

## 1. Informazioni generali

Diggio Agent IA è un'estensione per Google Chrome sviluppata da **Antonio Di Giorgio** (Diggio3000). Questa Privacy Policy descrive come l'Estensione gestisce i dati dell'utente.

---

## 2. Dati raccolti e archiviazione

L'Estensione archivia localmente sul dispositivo dell'utente le seguenti informazioni:

- API Key del provider AI scelto (OpenAI, Anthropic, Groq, OpenRouter, Perplexity, Ollama o endpoint custom)
- Endpoint API e nome del provider selezionato
- Modello AI selezionato
- Cronologia delle sessioni di chat
- Template di task salvati dall'utente
- Automazioni programmate create dall'utente
- Dati del Form Filler inseriti dall'utente

> **Tutti i dati sono archiviati esclusivamente tramite le API di Chrome (`chrome.storage.sync` e `chrome.storage.local`) e non vengono mai trasmessi a server controllati dallo sviluppatore.**

---

## 3. Trasmissione dei dati

L'Estensione invia dati esclusivamente agli endpoint API configurati dall'utente stesso (es. `api.openai.com`, `api.anthropic.com`, `api.groq.com`, ecc.) per elaborare i task richiesti. Lo sviluppatore non ha accesso a questi dati né li riceve.

Le comunicazioni con i provider AI includono:
- Il testo dei task inseriti dall'utente
- Il contenuto delle pagine web visitate durante l'esecuzione dei task
- Eventuali immagini allegate dall'utente

Queste trasmissioni avvengono direttamente tra il browser dell'utente e il provider AI scelto, nel rispetto delle rispettive Privacy Policy dei provider.

---

## 4. Permessi Chrome utilizzati

| Permesso | Motivo |
|----------|--------|
| `debugger` | Connessione al Chrome DevTools Protocol per navigare pagine, cliccare elementi, scattare screenshot e leggere il contenuto DOM — funzionalità core dell'agente AI |
| `tabs` | Leggere e gestire le schede del browser per selezionare la scheda target dell'agente |
| `scripting` | Eseguire script nelle pagine per interagire con elementi e leggere contenuti |
| `storage` | Salvare impostazioni, cronologia e template localmente sul dispositivo |
| `sidePanel` | Mostrare il pannello laterale dell'estensione |
| `activeTab` | Accedere alla scheda attiva corrente |
| `alarms` | Programmare l'esecuzione automatica dei task (automazioni) anche a pannello chiuso |
| `notifications` | Mostrare notifiche Chrome al completamento delle automazioni |
| `<all_urls>` | Consentire all'agente di navigare e interagire con qualsiasi sito web, come richiesto dai task dell'utente |

---

## 5. Dati condivisi con terze parti

Lo sviluppatore **non vende, non condivide e non trasmette** alcun dato dell'utente a terze parti. I dati inviati ai provider AI sono soggetti alle rispettive Privacy Policy di quei servizi, con cui l'utente ha un rapporto diretto e indipendente.

---

## 6. Sicurezza

Le API Key sono archiviate tramite `chrome.storage.sync`, cifrato da Chrome e sincronizzato in modo sicuro tra i dispositivi dell'utente tramite il suo account Google. Lo sviluppatore non ha mai accesso a queste chiavi.

---

## 7. Minori

L'Estensione non è destinata a utenti di età inferiore ai 13 anni. Lo sviluppatore non raccoglie consapevolmente dati personali di minori.

---

## 8. Modifiche a questa Privacy Policy

Eventuali aggiornamenti saranno pubblicati su questa pagina con la data di aggiornamento. L'uso continuato dell'Estensione dopo le modifiche costituisce accettazione della nuova Policy.

---

## 9. Contatti

**Antonio Di Giorgio** — per tutti Diggio3000

📧 [diggiotelefonia@gmail.com](mailto:diggiotelefonia@gmail.com)

---

*Diggio Agent IA · Sviluppato da Antonio Di Giorgio · 2026*
