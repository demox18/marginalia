# Marginalia

**Registra, trascrivi e studia le tue lezioni.** Per Mac e Windows. Le registrazioni non escono dal tuo computer.

👉 **[Scarica l'ultima versione](../../releases/latest)** · Sito: [demoxsites.altervista.org/marginalia](https://demoxsites.altervista.org/marginalia/)

| Sistema | File | Requisiti |
|---|---|---|
| Mac | `Marginalia.dmg` | Mac con chip Apple (M1 o successivi), macOS 13+ |
| Windows | `Marginalia-Windows.zip` | Windows 10 o 11, 64 bit |

## Cosa fa
- 🎙️ Registra la lezione in una finestrella mentre prendi appunti, con trascrizione in diretta e poi accurata, **sul tuo computer**.
- 📝 Appunti come su carta: formule, frazioni, checklist, disegni, foto, tabelle; divisi per materia.
- 🧠 Riassunti, mappe concettuali, flashcard e quiz, fatti da te o dall'AI.
- ✳️ Tutor AI sulla lezione, anche con un'AI che gira sul tuo computer (nessun dato inviato).
- 🏛️ Materiali dei docenti dell'Università di Cagliari, scaricati per usarli offline.
- 🎨 Temi, colori, sfondi, icone, foto e nickname.

## Perché puoi fidarti
- **Le tue lezioni restano tue**: lezioni, audio e appunti stanno in una cartella del tuo computer.
- **Niente dati inviati di nascosto**: al primo avvio l'app scarica i programmi per la trascrizione e l'AI locale; dopo, va su internet solo per ciò che fai tu (materiali UniCa, un'AI online se la scegli). Le tue lezioni e i tuoi audio non vengono caricati da nessuna parte. Il feedback parte solo quando premi invia, dalla tua app di posta.
- **Controlla che il file sia quello originale**: in ogni versione c'è `SHA256SUMS.txt` con l'impronta di ogni file. Sul Mac: `shasum -a 256 Marginalia.dmg` · su Windows (PowerShell): `Get-FileHash Marginalia-Windows.zip`. Le due impronte devono essere identiche.
- **Scaricala solo da qui o dal sito ufficiale**: altre copie potrebbero essere state modificate.
- **Perché il Mac ti avvisa?** Marginalia non è firmata con un certificato Apple, quindi al primo avvio dal DMG compare un avviso: è normale.

## Installazione
**Mac**: apri il DMG e trascina Marginalia in Applicazioni. Se all'apertura compare un avviso, vai in *Impostazioni di Sistema → Privacy e sicurezza* e premi **Apri comunque**.

**Windows**: fai clic destro su Start, scegli *Terminale* (o *Windows PowerShell*), incolla questa riga e premi Invio:

```powershell
irm https://demoxsites.altervista.org/marginalia/installa-windows.ps1 | iex
```

Scarica `Marginalia-Windows.zip`, controlla che sia quello originale e installa Marginalia nella tua cartella utente, senza permessi di amministratore. Le icone avviano Python ufficiale, firmato dalla Python Software Foundation, quindi Windows non mostra «Windows ha protetto il PC». Puoi leggere prima cosa fa: [installa-windows.ps1](https://demoxsites.altervista.org/marginalia/installa-windows.ps1). Si disinstalla da *Impostazioni → App*.

## Segnalare un problema
Nell'app usa **💬 Feedback** (puoi allegare foto), oppure apri una [segnalazione](../../issues) qui su GitHub.

---
Il codice sorgente di Marginalia non è pubblico. © 2026 demox — tutti i diritti riservati. Vedi [LICENZA](LICENZA.md).
