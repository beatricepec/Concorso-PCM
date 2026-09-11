# Concorso PCM — profilo DTD2

Schemi di studio per il concorso alla Presidenza del Consiglio dei ministri,
**Dipartimento per la trasformazione digitale**, profilo **DTD2 — Specialista di
comunicazione e sistemi di gestione e informatici**.

> ⚠️ **Fanno fede solo il bando e gli avvisi su [inPA](https://www.inpa.gov.it).**
> Questi schemi sono materiale di studio personale, non una fonte ufficiale.
> Ultimo allineamento dei contenuti: **31 agosto 2026**.

---

## La prova in una riga

60 quesiti in 80 minuti · soglia **42/60 (70%)** · materie 40 + situazionali 12 + inglese 8.

## Indice

| # | Materia | Quesiti stimati | Schema |
|---|---------|-----------------|--------|
| 0 | Struttura della prova e strategia | — | [00-prova-e-strategia.md](00-prova-e-strategia.md) |
| 1 | Project & Program management | ~5 | [01-project-management.md](01-project-management.md) |
| 2 | Comunicazione pubblica e istituzionale | ~5 | [02-comunicazione-pubblica.md](02-comunicazione-pubblica.md) |
| 3 | Gestione dei sistemi informativi | ~5 | [03-sistemi-informativi.md](03-sistemi-informativi.md) |
| 4 | Digital marketing e social media | ~5 | [04-digital-marketing.md](04-digital-marketing.md) |
| 5 | Intelligenza artificiale | ~5 | [05-intelligenza-artificiale.md](05-intelligenza-artificiale.md) |
| 6 | Appalti pubblici (D.lgs. 36/2023) | ~5 | [06-appalti-pubblici.md](06-appalti-pubblici.md) |
| 7 | Privacy, sicurezza dei dati e cybersicurezza | ~5 | [07-privacy-e-cybersicurezza.md](07-privacy-e-cybersicurezza.md) |
| 8 | PNRR e misure sulla digitalizzazione | ~5 | [08-pnrr-digitale.md](08-pnrr-digitale.md) |
| 9 | Ordinamento della PCM | ~5 | [09-ordinamento-pcm.md](09-ordinamento-pcm.md) |
| 10 | Situazionali + inglese B1 | 20 | [10-situazionali-e-inglese.md](10-situazionali-e-inglese.md) |

> La ripartizione dei 40 quesiti fra le 9 materie **non è dichiarata nel bando**: quella in
> tabella è un'ipotesi di lavoro (distribuzione uniforme) utile solo a bilanciare le ore di studio.

## Cheatsheet trasversali

- [Numeri, soglie e termini](cheat-numeri-e-soglie.md) — il file da ripassare il giorno prima
- [Formule](cheat-formule.md) — EVM, PERT, metriche, engagement rate
- [Acronimi e sigle](cheat-acronimi.md) — glossario A-Z
- [Norme chiave in ordine cronologico](cheat-norme-chiave.md)

## Strumenti

- [Piano di studio 8 settimane](piano-di-studio.md) — con checkbox di avanzamento
- [flashcards-numeri.csv](flashcards-numeri.csv) — importabile in Anki (separatore `;`)

---

## Come è fatto ogni schema

Tutti i file materia seguono la stessa struttura, così il ripasso diventa meccanico:

1. **Mappa** — mindmap Mermaid della materia (GitHub la renderizza nativamente)
2. **Schemi** — tabelle e alberi, mai prosa
3. **Numeri da sapere a memoria** — la parte che frutta più punti per minuto
4. **Trappole d'esame** — distinzioni su cui i quiz giocano di più
5. **Autoverifica** — domande secche con risposta in blocco `<details>` richiudibile
6. **Fonti** — link primari
7. **Checklist di padronanza** — checkbox da spuntare quando l'argomento è chiuso

## Come usarlo su GitHub

```bash
git init
git add .
git commit -m "Schemi DTD2"
git branch -M main
git remote add origin git@github.com:<tuo-utente>/concorso-pcm-dtd2.git
git push -u origin main
```

Consigli d'uso:

- **Repo privata**, così puoi annotare liberamente.
- Spunta le checkbox direttamente dall'interfaccia web di GitHub: il commit è automatico e
  ti resta lo storico di quando hai chiuso ciascun argomento.
- Usa le **Issues** per gli errori: una issue per ogni quesito sbagliato nei simulatori,
  con label `materia:06-appalti`, `tipo:numero`, `tipo:distinzione`. Prima della prova
  rileggi solo le issue aperte: è il tuo quaderno degli errori, già filtrabile.
- Usa un **Project (board)** con colonne `Da fare` / `Studiato` / `Ripassato 1` / `Ripassato 2`
  per il ripasso a intervalli.
- Metti la data dell'ultimo ripasso nel messaggio di commit: `ripasso: 06-appalti soglie`.

## Avvertenza sull'aggiornamento normativo

Le materie **5, 6, 7 e 8** sono in evoluzione continua (decreti attuativi della L. 132/2025
attesi entro il 10 ottobre 2026, modifiche all'AI Act del Digital Omnibus, correttivi al
codice appalti, chiusura del PNRR il 31 agosto 2026).
Nell'ultima settimana prima della prova dedica un'ora a verificare lo stato di questi quattro fronti.
