---
layout: default
title: Privacy Policy – Medy Moe
---

# Informativa sulla privacy

**Medy Moe · Medy Moe's · Medy Moe del facilitatore** — Ultimo aggiornamento: 19 ottobre 2026

> Questa informativa fa fede nella versione italiana. La versione inglese, più in basso, è offerta a titolo informativo.

---

## 1. Titolare del trattamento

Andrea Guido Caiulo
Contatto: [support@medymoe.com](mailto:support@medymoe.com)

---

## 2. Le tre app e chi le usa

Medy Moe è un unico servizio distribuito in tre app:

- **Medy Moe** — per il **Praticante**, chi medita. Si scarica tramite il QR del Luogo a cui si è abbonati.
- **Medy Moe's** — per il **Luogo**, il centro che organizza i Giri (sessioni di gruppo a orario fisso) e gestisce le Sale.
- **Medy Moe del facilitatore** — per il **facilitatore**, chi conduce gli eventi di un Luogo.

Le tre app parlano con lo stesso server. I dati descritti qui sotto valgono per tutte e tre, salvo dove è detto altrimenti.

---

## 3. Dati che restano sul tuo dispositivo

Ogni app conserva nella memoria locale del dispositivo (o del browser, nella versione web) ciò che serve a funzionare anche senza connessione:

- le pratiche personali e le prenotazioni dei Giri sulle Carte;
- lo storico delle sessioni completate (data, durata, meditazione) su cui si calcolano le Statistiche, e gli eventuali azzeramenti;
- le impostazioni: lingua, tema, notifiche, Modalità non udenti;
- l'**alias** e l'avatar con cui ti presenti nella Bacheca;
- i Luoghi che hai aggiunto (via QR o codice), le Sale che hai fissato in cima, i posti alle riunioni che hai preso, le iscrizioni agli eventi;
- una copia delle note della Bacheca che hai letto o scritto;
- il token di accesso al tuo account (nella memoria sicura del sistema) e, sul telefono, il token per le notifiche push;
- la registrazione dell'avvenuta lettura di *Manuale e Regole* (i dieci punti essenziali).

Questi dati vengono eliminati disinstallando l'app o cancellando i dati del browser. Le Statistiche sono legate all'account: da sloggato non sono visibili, ma non vengono cancellate.

---

## 4. Dati trattati sul server

Per usare l'app oltre la modalità dimostrativa serve un account. Il server conserva:

### 4.1 Account

- **email** e **password** (conservata come hash con bcrypt, mai in chiaro);
- il **ruolo** (Praticante, Luogo, facilitatore) e lo **stato** dell'account (attivo, sospeso, chiuso);
- per il solo **facilitatore**: **nome e cognome** e la data dell'accertamento del ruolo;
- per il **Luogo**: il nome del Luogo, le Sale, gli orari dei Giri, le riunioni e gli eventi che pubblica (con il nome del facilitatore che li conduce), le lingue scelte per sottotitoli e TV;
- la data e la versione con cui hai preso visione di *Manuale e Regole*;
- le tue preferenze sincronizzate (notifiche, tema, lingua).

### 4.2 Pratica e Statistiche

- il **contatore** delle sessioni completate e dei minuti totali meditati (per sempre, fino alla cancellazione dell'account);
- la sessione **in corso** (meditazione, durata, fase, orario di avvio). Le righe delle singole sessioni vengono **distrutte ogni giorno**: resta solo il contatore. Lo storico dettagliato vive sul tuo dispositivo (§ 3).

### 4.3 Bacheca (solo Praticante)

La Bacheca è lo spazio condiviso da chi ha cominciato lo stesso Giro lo stesso giorno. Ci si entra solo dopo un consenso esplicito, chiesto nell'app la prima volta. Il server conserva:

- il **testo** della tua nota, con l'**alias** e l'avatar scelti da te; gli altri partecipanti non vedono mai la tua email, ma uno **pseudonimo** derivato dal Giro, diverso in ogni Bacheca;
- la tua appartenenza al gruppo (quando sei entrato, l'ultimo passaggio, l'eventuale uscita);
- chi ha letto chi (per far funzionare la regola «leggi solo se hai scritto» e il giudizio del gruppo);
- le **segnalazioni** che fai o ricevi, i **congelamenti** della Bacheca, le **infrazioni** confermate dal gruppo, i **fermi** e le **riammissioni**;
- gli utenti che hai **bloccato**.

**Cosa succede alla terza infrazione.** Se il gruppo conferma tre infrazioni a tuo carico, la Bacheca si chiude per te finché non ti riammette di persona uno dei Luoghi nelle cui Bacheche sono nate quelle infrazioni. Per fissare quell'incontro, **ognuno di quei Luoghi vede il tuo indirizzo email**, anche se da lui ne è nata una sola: ognuno di loro può riammetterti. I Luoghi dove non è nata nessuna delle tue infrazioni non lo vedono. Il tuo alias e il contenuto delle tue note non vengono mostrati a nessuno di loro.

**Segnalazioni.** Una segnalazione genera un'email interna al titolare che contiene il motivo, la data, gli identificativi della Bacheca e della nota, l'email di chi ha scritto e di chi segnala, e il **testo integrale** della nota segnalata. È l'unica copia del testo conservata oltre le 24 ore ed è usata solo per i casi che richiedono un intervento diretto (contenuto illecito, obbligo di legge): il funzionamento ordinario della Bacheca è deciso dal gruppo.

### 4.4 Riunioni ed eventi

- il **posto** che prendi alla riunione di un Giro (chiave del Giro e data della riunione), la **lista d'attesa** e l'invito con la sua scadenza;
- le iscrizioni alle riunioni di Sala e agli **eventi** del Luogo (Luogo, evento, ciclo, data);
- le Sale che hai fissato in cima per ogni Luogo.

Il Luogo vede l'elenco degli iscritti alle proprie riunioni ed eventi con l'**alias**; il facilitatore vede gli iscritti ai propri eventi.

### 4.5 Note private del facilitatore

Il facilitatore può scrivere **note private** legate a un evento o a un iscritto di un Luogo. Le vede solo lui; sono conservate un anno e cancellate con il suo account. Se una nota ti riguarda, puoi chiederne copia con la richiesta di accesso (§ 8).

### 4.6 Notifiche push

Se accetti le notifiche, l'app consegna al server un **token di consegna** del dispositivo. Serve solo a recapitare le notifiche del servizio (posto liberato, invito dalla lista d'attesa). Viene cancellato al logout e quando il dispositivo non è più raggiungibile.

### 4.7 Diagnostica (Sentry)

In caso di errore l'app invia un rapporto a **Sentry** (sentry.io): tipo di errore, traccia tecnica, sistema operativo, versione dell'app, dati di prestazione. Se sei loggato, il rapporto porta **uno pseudonimo** al posto della tua email: un'impronta che il nostro server calcola dall'email, con cui ritroviamo i rapporti che ti riguardano se ci scrivi per un problema. Nessun dato viene usato per pubblicità o tracciamento.

### 4.8 Le TV del Luogo

Le pagine per la TV (Sala, Vetrina, Pratica) mandano al server un **battito** anonimo: presenza, pagina aperta, meditazione in corso, versione, eventuale errore del player. Non contiene dati personali e vive solo nella memoria del server; serve al Luogo per sapere dal Controllo sale se la TV è accesa.

### 4.9 Registro delle richieste GDPR

Ogni richiesta di esportazione o cancellazione (§ 8) è annotata in un registro con tipo, email, data, **indirizzo IP** e **user agent**. Il registro sopravvive alla cancellazione dell'account: è la prova che la richiesta è stata evasa (art. 5.2 GDPR).

---

## 5. Permessi del dispositivo

- **Fotocamera**: solo per inquadrare il QR del Luogo. Nessuna immagine viene salvata o inviata.
- **Notifiche**: promemoria locali e notifiche push del servizio, solo se le accetti.
- **Audio**: l'app regola il volume per le meditazioni. Non registra mai (il permesso al microfono è escluso dalle app).

L'app **non** accede a posizione, contatti, dati biometrici, e non contiene pubblicità né strumenti di tracciamento.

---

## 6. Base giuridica e finalità

| Trattamento | Base giuridica |
|---|---|
| Account, pratica, prenotazioni, riunioni, eventi, notifiche | esecuzione del contratto (art. 6.1.b GDPR) |
| Bacheca | consenso esplicito (art. 6.1.a), revocabile lasciando la Bacheca |
| Moderazione, segnalazioni, esposizione dell'email alla terza infrazione ai Luoghi dove sono nate le infrazioni | legittimo interesse a tenere sicuro uno spazio chiuso (art. 6.1.f) e obblighi di legge (art. 6.1.c) |
| Diagnostica | legittimo interesse a far funzionare l'app (art. 6.1.f) |
| Registro delle richieste GDPR | obbligo di legge (art. 6.1.c) |

---

## 7. Conservazione dei dati

| Dato | Conservazione |
|---|---|
| Dati locali (§ 3) | sul dispositivo fino alla disinstallazione |
| Account, contatori, preferenze, presa visione di *Manuale e Regole* | fino alla cancellazione dell'account |
| Righe delle singole sessioni sul server | distrutte ogni giorno; resta il contatore |
| Nota della Bacheca | **24 ore dall'ultima modifica**, poi cancellata automaticamente. Nessuna copia oltre le 24 ore, tranne il testo contenuto nell'email di un'eventuale segnalazione |
| Appartenenza a una Bacheca | 108 giorni dall'ingresso |
| Posto alla riunione | fino al giorno dopo la riunione |
| Invito dalla lista d'attesa | 30 minuti |
| Iscrizioni a riunioni di Sala | fino a due giorni dopo la riunione |
| Iscrizioni a eventi | 30 giorni dopo la fine dell'evento; gli eventi restano pubblicati per un anno |
| Segnalazioni di una nota della Bacheca | 30 giorni (più a lungo solo finché il giudizio del gruppo su quella Bacheca è ancora aperto) |
| Infrazioni in Bacheca | una si cancella dopo un mese di calendario intero senza nuove infrazioni, due dopo due mesi; tre restano finché il Luogo non ti riammette, e allora si cancellano |
| Fermi (la Bacheca da saltare dopo una segnalazione) | 7 giorni dopo essere stati scontati |
| Utenti bloccati | finché chi ha bloccato non sblocca, o fino alla cancellazione dell'account |
| Note private del facilitatore | un anno, o la cancellazione del suo account |
| Token per le notifiche push | fino al logout, o finché il dispositivo è raggiungibile |
| Token di reimpostazione password | fino all'uso o alla scadenza |
| Rapporti di errore (Sentry) | 90 giorni |
| Battito delle TV | solo in memoria; sparisce al riavvio del server |
| Registro delle richieste GDPR | conservato anche dopo la cancellazione dell'account |

---

## 8. I tuoi diritti (artt. 15-22 GDPR)

Dalle **Impostazioni → Privacy e dati** puoi, in qualsiasi momento e anche con l'account sospeso o chiuso:

- **esportare** tutti i tuoi dati: ricevi via email un file JSON con tutto ciò che il server conserva su di te;
- **cancellare** l'account: tutti i dati del server vengono eliminati, tranne il registro delle richieste (§ 4.9).

Hai inoltre diritto di rettifica, limitazione, opposizione e portabilità, e di proporre reclamo al Garante per la protezione dei dati personali. Per esercitare questi diritti scrivi a [support@medymoe.com](mailto:support@medymoe.com).

---

## 9. Destinatari e trasferimenti

I dati sono trattati dal titolare e dai fornitori tecnici necessari al servizio:

- il **fornitore di hosting** del server e del database;
- **Sentry** (Functional Software, Inc.) per la diagnostica;
- il **servizio di posta** che recapita email di servizio, esportazioni e segnalazioni;
- **Expo** (650 Industries, Inc.) e, tramite Expo, **Apple** (APNs) e **Google** (FCM) per la consegna delle notifiche push;
- gli **store** (Apple App Store, Google Play), che gestiscono l'abbonamento: Medy Moe non vede mai i dati di pagamento;
- **Anthropic** (Anthropic Ireland Limited, per i servizi nell'Unione Europea), quando è attivo il risponditore automatico dell'assistenza: riceve solo l'oggetto e il testo visibile dei messaggi scritti a support@medymoe.com (al massimo 4.000 caratteri), senza indirizzo email, allegati o intestazioni, per proporre la risposta;
- **GitHub** (GitHub, Inc.), che con GitHub Pages ospita le pagine di questa informativa e dei Termini: registra l'indirizzo IP di chi le apre, per sicurezza;
- **Netlify** (Netlify, Inc.), che ospita il sito medymoe.com: riceve l'indirizzo IP di chi lo visita, per mostrargli le pagine.

Nessun dato è venduto o ceduto a terzi per finalità proprie. Se un fornitore tratta dati fuori dall'Unione Europea, il trasferimento avviene sulla base delle clausole contrattuali standard della Commissione Europea o, per i fornitori che vi aderiscono, della decisione di adeguatezza sul Quadro UE-USA per la protezione dei dati personali (EU-U.S. Data Privacy Framework).

---

## 10. Minori

Le app sono riservate ai **maggiorenni**. Al momento della registrazione il Praticante dichiara la maggiore età. Non raccogliamo consapevolmente dati di minori: se ne veniamo a conoscenza, cancelliamo l'account.

---

## 11. Modifiche a questa informativa

Le modifiche vengono pubblicate su questa pagina con la data di aggiornamento. Per modifiche sostanziali gli utenti registrati ricevono un avviso via email.

---

## 12. Contatti

**Andrea Guido Caiulo**
[support@medymoe.com](mailto:support@medymoe.com)

---

[English version below](#english)

---

<a name="english"></a>

# Privacy Policy (English)

**Medy Moe · Medy Moe's · Medy Moe del facilitatore** — Last updated: October 19, 2026

> The Italian version of this policy is the binding one. This English version is provided for information only.

---

## 1. Data Controller

Andrea Guido Caiulo
Contact: [support@medymoe.com](mailto:support@medymoe.com)

---

## 2. The three apps and who uses them

Medy Moe is one service delivered as three apps:

- **Medy Moe** — for the **Praticante**, the person who meditates. Downloaded through the QR code of the Luogo they subscribe to.
- **Medy Moe's** — for the **Luogo**, the centre that organises Giri (group sessions at fixed times) and manages its rooms (Sale).
- **Medy Moe del facilitatore** — for the **facilitatore**, who leads a Luogo's events.

All three apps talk to the same server. The data below applies to all three unless stated otherwise.

---

## 3. Data that stays on your device

Each app keeps in the device's local storage (or the browser's, on the web) what it needs to work offline:

- personal practices and Giro bookings on the Cards;
- the history of completed sessions (date, duration, meditation) used for Statistics, and any resets;
- settings: language, theme, notifications, Deaf mode;
- the **alias** and avatar you use on the board (Bacheca);
- the Luoghi you added (via QR or code), rooms you pinned, meeting seats you took, event sign-ups;
- a copy of board notes you read or wrote;
- your account access token (in the system's secure storage) and, on phones, the push notification token;
- the record that you read *Manual and Rules* (the ten essential points).

This data is deleted when you uninstall the app or clear browser data. Statistics belong to the account: they are hidden while logged out, not deleted.

---

## 4. Data processed on the server

Beyond demo mode, the app requires an account. The server stores:

### 4.1 Account

- **email** and **password** (stored as a bcrypt hash, never in plain text);
- the **role** (Praticante, Luogo, facilitatore) and the account **status** (active, suspended, closed);
- for the **facilitatore** only: **first and last name** and the date the role was verified;
- for the **Luogo**: its name, rooms, Giro schedule, meetings and events it publishes (including the name of the facilitatore leading them), languages chosen for subtitles and TVs;
- the date and version of your acknowledgement of *Manual and Rules*;
- your synced preferences (notifications, theme, language).

### 4.2 Practice and Statistics

- the **counter** of completed sessions and total minutes meditated (kept until account deletion);
- the session **in progress** (meditation, duration, stage, start time). Individual session rows are **deleted daily**: only the counter remains. Detailed history lives on your device (§ 3).

### 4.3 Board (Praticante only)

The board is shared by people who started the same Giro on the same day. You enter it only after explicit consent, asked in the app the first time. The server stores:

- the **text** of your note, with the **alias** and avatar you chose; other participants never see your email, but a **pseudonym** derived from the Giro, different in every board;
- your membership (when you joined, last activity, whether you left);
- who read whom (needed for the "read only if you wrote" rule and the group's judgement);
- **reports** you make or receive, board **freezes**, **infractions** confirmed by the group, **holds** and **readmissions**;
- users you **blocked**.

**What happens at the third infraction.** If the group confirms three infractions against you, the board closes for you until one of the Luoghi on whose boards those infractions arose readmits you in person. To arrange that meeting, **each of those Luoghi sees your email address**, even if only one of them arose there: any of them can readmit you. Luoghi where none of your infractions arose do not see it. Your alias and the content of your notes are not shown to any of them.

**Reports.** A report generates an internal email to the controller containing the reason, the date, the board and note identifiers, the emails of the author and the reporter, and the **full text** of the reported note. It is the only copy of the text kept beyond 24 hours and is used only for cases requiring direct intervention (unlawful content, legal obligation): the board's ordinary operation is decided by the group.

### 4.4 Meetings and events

- the **seat** you take at a Giro's meeting (Giro key and meeting date), the **waiting list** and the invitation with its expiry;
- sign-ups to room meetings and to the Luogo's **events** (Luogo, event, cycle, date);
- the rooms you pinned for each Luogo.

The Luogo sees the list of people signed up to its meetings and events by **alias**; the facilitatore sees the people signed up to their events.

### 4.5 The facilitatore's private notes

The facilitatore may write **private notes** linked to an event or to a person signed up at a Luogo. Only they can see them; notes are kept for one year and deleted with their account. If a note concerns you, you may request a copy through an access request (§ 8).

### 4.6 Push notifications

If you accept notifications, the app hands the server a device **delivery token**. It is used only to deliver service notifications (seat freed, invitation from the waiting list). It is deleted at logout and when the device is no longer reachable.

### 4.7 Diagnostics (Sentry)

On errors the app sends a report to **Sentry** (sentry.io): error type, technical trace, operating system, app version, performance data. If you are logged in, the report carries **a pseudonym** instead of your email: a fingerprint our server computes from your email, which lets us find the reports about you if you write to us about a problem. No data is used for advertising or tracking.

### 4.8 The Luogo's TVs

The TV pages (Sala, Vetrina, Pratica) send the server an anonymous **heartbeat**: presence, open page, current meditation, version, any player error. It contains no personal data and lives only in the server's memory; it lets the Luogo see from its control panel whether the TV is on.

### 4.9 GDPR request log

Every export or deletion request (§ 8) is logged with type, email, date, **IP address** and **user agent**. The log survives account deletion: it is the evidence that the request was fulfilled (Art. 5.2 GDPR).

---

## 5. Device permissions

- **Camera**: only to scan the Luogo's QR code. No image is stored or sent.
- **Notifications**: local reminders and service push notifications, only if you accept.
- **Audio**: the app adjusts volume for meditations. It never records (the microphone permission is excluded from the apps).

The app does **not** access location, contacts or biometric data, and contains no advertising or tracking tools.

---

## 6. Legal basis and purposes

| Processing | Legal basis |
|---|---|
| Account, practice, bookings, meetings, events, notifications | performance of the contract (Art. 6.1.b GDPR) |
| Board | explicit consent (Art. 6.1.a), withdrawable by leaving the board |
| Moderation, reports, disclosure of the email at the third infraction to the Luoghi where the infractions arose | legitimate interest in keeping a closed space safe (Art. 6.1.f) and legal obligations (Art. 6.1.c) |
| Diagnostics | legitimate interest in keeping the app working (Art. 6.1.f) |
| GDPR request log | legal obligation (Art. 6.1.c) |

---

## 7. Data retention

| Data | Retention |
|---|---|
| Local data (§ 3) | on the device until uninstall |
| Account, counters, preferences, acknowledgement of *Manual and Rules* | until account deletion |
| Individual session rows on the server | deleted daily; the counter remains |
| Board note | **24 hours from the last edit**, then deleted automatically. No copy beyond 24 hours, except the text contained in the email of a report |
| Board membership | 108 days from joining |
| Meeting seat | until the day after the meeting |
| Waiting-list invitation | 30 minutes |
| Room meeting sign-ups | until two days after the meeting |
| Event sign-ups | 30 days after the event ends; events stay published for one year |
| Reports of a board note | 30 days (longer only while the group's judgement on that board is still open) |
| Board infractions | one is deleted after a full calendar month with no new infractions, two after two months; three remain until the Luogo readmits you, and are then deleted |
| Pauses (the board to skip after a report) | 7 days after being served |
| Blocked users | until the blocker unblocks, or until account deletion |
| Facilitatore's private notes | one year, or deletion of their account |
| Push notification token | until logout, or while the device is reachable |
| Password reset token | until used or expired |
| Error reports (Sentry) | 90 days |
| TV heartbeat | memory only; gone at server restart |
| GDPR request log | kept after account deletion |

---

## 8. Your rights (Arts. 15-22 GDPR)

From **Settings → Privacy and data** you can, at any time and even with a suspended or closed account:

- **export** all your data: you receive by email a JSON file with everything the server holds about you;
- **delete** the account: all server data is erased, except the request log (§ 4.9).

You also have the rights to rectification, restriction, objection and portability, and to lodge a complaint with the Italian Data Protection Authority (Garante). To exercise these rights write to [support@medymoe.com](mailto:support@medymoe.com).

---

## 9. Recipients and transfers

Data is processed by the controller and by the technical providers the service needs:

- the **hosting provider** of the server and database;
- **Sentry** (Functional Software, Inc.) for diagnostics;
- the **email service** delivering service emails, exports and reports;
- **Expo** (650 Industries, Inc.) and, through Expo, **Apple** (APNs) and **Google** (FCM) for push delivery;
- the **stores** (Apple App Store, Google Play), which manage the subscription: Medy Moe never sees payment data;
- **Anthropic** (Anthropic Ireland Limited, for services in the European Union), when the automatic support responder is active: it receives only the subject and visible text of messages written to support@medymoe.com (at most 4,000 characters), without email address, attachments or headers, to suggest the reply;
- **GitHub** (GitHub, Inc.), which hosts the pages of this policy and of the Terms on GitHub Pages: it logs the IP address of whoever opens them, for security;
- **Netlify** (Netlify, Inc.), which hosts the website medymoe.com: it receives the IP address of visitors, to serve them the pages.

No data is sold or handed to third parties for their own purposes. Where a provider processes data outside the European Union, the transfer relies on the European Commission's standard contractual clauses or, for providers that adhere to it, on the adequacy decision for the EU-U.S. Data Privacy Framework.

---

## 10. Minors

The apps are for **adults only**. At registration the Praticante declares to be of age. We do not knowingly collect data from minors: if we learn of it, we delete the account.

---

## 11. Changes to this policy

Changes are published on this page with the update date. For material changes, registered users receive an email notice.

---

## 12. Contact

**Andrea Guido Caiulo**
[support@medymoe.com](mailto:support@medymoe.com)
