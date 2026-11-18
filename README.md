# Ciao! Questo è Kobi 🤖

**Kobi** è un piccolo robot che vive sul tuo schermo. Trascinaci sopra una cartella e si apre il Terminale già dentro quella cartella, con **Claude Code** avviato.

Niente più «apri il Terminale, scrivi `cd `, trascina la cartella, Invio, scrivi `claude`». Basta trascinare la cartella su Kobi.

* **Una cartella** → si apre lì.
* **Un file** → si apre la cartella che lo contiene.
* **Più cartelle insieme** → una finestra di Terminale per ciascuna (fino a 5).
* **Spostare Kobi** → trascinalo dove vuoi: si ricorda la posizione.
* **Clic destro su Kobi** → Impostazioni, Controlla aggiornamenti, Nascondi, Esci.

---

### ✅ Prima di iniziare: serve Claude Code

Kobi avvia `claude` nel Terminale, quindi deve essere già installato sul tuo Mac. Se nel Terminale vedi *«command not found: claude»*, installalo seguendo la guida ufficiale: <https://docs.claude.com/en/docs/claude-code/setup>.

---

### 🚀 Download e primo avvio

👉 **[Scarica l'ultima versione di Kobi (.zip)](https://github.com/stegidi/kobi-releases/releases/latest/download/Kobi.zip)**

#### 1. Trascina l'app
Apri lo zip ed estrai **`Kobi.app`**. Poi **trascinala nella cartella Applicazioni**.

#### 2. Il primo avvio (perché macOS mostra un avviso?)
Ho fatto Kobi per me e per voi amici, quindi non pago ad Apple i 99 $ all'anno per diventare «sviluppatore identificato». Per questo, la prima volta macOS dice che *non può verificare l'app*.

**Si sistema in un minuto, e solo la prima volta:**

1. Apri **Kobi** dalla cartella Applicazioni. Compare l'avviso: clicca **Fine** (non «Sposta nel Cestino»).
2. Apri **Impostazioni di Sistema → Privacy e sicurezza** e scorri in basso fino a *«Kobi è stato bloccato…»*.
3. Clicca **Apri comunque** e conferma con la password del Mac (o Touch ID).
4. Kobi si apre: vedi il robottino in basso a destra.

*(Oppure, dal Terminale, incolla questo comando e premi Invio, poi apri Kobi normalmente:)*
```bash
xattr -cr /Applications/Kobi.app
```

#### 3. Il permesso per il Terminale
La prima volta che trascini una cartella su Kobi, macOS chiede:
*«Kobi vuole controllare "Terminale"»*. Clicca **Consenti**.

Serve a Kobi per aprire il Terminale nella cartella giusta e scriverci `claude` al posto tuo. Non fa nient'altro.

Se per sbaglio hai cliccato «Non consentire»: **Impostazioni di Sistema → Privacy e sicurezza → Automazione → Kobi** e attiva **Terminale**. (Kobi te lo ricorda con un messaggio e un pulsante che ti porta lì.)

La prima volta che usi Claude Code in una cartella, sarà Claude Code stesso a chiederti se ti fidi di quella cartella: è normale.

---

### ⚙️ Impostazioni (clic destro su Kobi → Impostazioni…)

* **Sempre in primo piano**: Kobi resta sopra tutte le finestre (attivo all'inizio).
* **Apri all'avvio del Mac**: Kobi parte da solo quando accendi il Mac (spento all'inizio).

**Nascondere Kobi**: clic destro → *Nascondi Kobi*. Per farlo ricomparire, riapri Kobi da Applicazioni o da Spotlight.
**Chiudere Kobi**: clic destro → *Esci da Kobi*.

---

### 🔄 E gli aggiornamenti?

**Non devi fare niente.** Kobi controlla da solo se ci sono nuove versioni, te lo dice e con un clic si aggiorna e si riavvia. Puoi controllare quando vuoi con clic destro → **Controlla aggiornamenti…**. Gli aggiornamenti non mostrano più l'avviso di macOS.

---

<details>
<summary>🇬🇧 English version (click to expand)</summary>

### Meet Kobi 🤖

**Kobi** is a tiny robot that lives on your screen. Drop a folder on it and Terminal opens in that folder with **Claude Code** already running.

* A folder opens itself; a file opens its containing folder; several folders open one Terminal window each (up to 5).
* Drag Kobi anywhere: it remembers its position.
* Right-click Kobi for Settings, Check for updates, Hide, Quit.

**Requirement**: Claude Code must be installed (<https://docs.claude.com/en/docs/claude-code/setup>).

#### Install

👉 **[Download the latest release (.zip)](https://github.com/stegidi/kobi-releases/releases/latest/download/Kobi.zip)**

1. Unzip and drag **`Kobi.app`** into **Applications**.
2. **First launch**: I don't pay Apple $99/year to be an "identified developer", so macOS can't verify the app. Open Kobi, click **Done**, then go to **System Settings → Privacy & Security**, scroll down to *"Kobi was blocked…"*, click **Open Anyway** and confirm. Only needed once. *(Or in Terminal: `xattr -cr /Applications/Kobi.app`.)*
3. **Terminal permission**: the first time you drop a folder, macOS asks *"Kobi wants to control Terminal"*: click **Allow**. If you denied it: **System Settings → Privacy & Security → Automation → Kobi → Terminal**.

To bring a hidden Kobi back, open it again from Applications or Spotlight.

#### Updates
Automatic: Kobi notifies you, updates itself and restarts. You can also right-click → **Controlla aggiornamenti…**.

</details>
