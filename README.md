# Dungeon Manager

Project manager a file singolo: un solo `taskflow_5.html`, nessuna dipendenza, nessun server.
Si apre con doppio clic e si sincronizza fra postazioni tramite un JSON in una cartella condivisa
(Drive / OneDrive / SharePoint), via File System Access API.

## Dove vive la copia viva

La copia **usata dal reparto** è quella su Google Drive:

```
Il mio Drive/AI work/taskflow_5.html
```

Questa repo è il **versionamento**: serve a tenere la storia e a poter tornare indietro.
Quando si modifica, si modifica il file su Drive e poi si aggiorna qui — non il contrario,
altrimenti le due copie divergono.

## Cosa c'è dentro

- **Today** — la giornata: in ritardo / oggi / prossimi 7 giorni, con scrittura rapida in italiano
- **Charter** — il patto del progetto: perché esiste, obiettivo, deliverable datati (che diventano
  milestone vere nel piano), fuori perimetro, vincoli live, rischi con contromisure, baseline,
  deriva, promesso vs consegnato
- **List / Board / Timeline / Map / Dashboard / Hours** — la timeline ha vista per attività e per
  risorsa e si creano dipendenze trascinando; la mappa è il grafo delle dipendenze con note adesive
- **Il consiglio** — rassegna a schermo intero e modalità ambiente per il monitor di reparto:
  verdetto, previsione della data di fine, cosa è cambiato dall'ultima volta, decisioni da prendere
- **Import** — Excel .xlsx letto davvero (zip + XML, senza librerie), CSV, XML di MS Project
- **Bestiario dei blocchi** e **taratura delle promesse** in Chronicles

Manuale completo dentro l'app: **Handbook**.
