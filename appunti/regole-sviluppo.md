# Regole di Sviluppo - Seminario IA

Regole operative per lo sviluppo e manutenzione del materiale del seminario.

---

## 📝 Regola: Brainstorming → Contenuti

**IMPORTANTE**: Quando si passa dalla fase di brainstorming/ideazione alla fase di scrittura contenuti definitivi, **aggiornare ENTRAMBI**:

1. **Appunti** (directory `appunti/`)
   - File markdown con dettagli completi
   - Script word-by-word
   - Note per relatore
   - Esempi, varianti, backup

2. **Presentazione** (directory `presentation/`)
   - Slide reveal.js
   - Contenuto visivo per pubblico
   - Note del relatore nelle slide
   - Immagini, animazioni

**Workflow corretto**:
```
Brainstorm in appunti/
     ↓
Refinement/feedback
     ↓
Scrittura definitiva
     ↓
AGGIORNA ENTRAMBI:
  - appunti/*.md
  - presentation/*/index.html (slide)
```

**Errore comune da evitare**:
❌ Aggiornare solo appunti e dimenticare le slide
❌ Aggiornare solo slide e dimenticare gli appunti

**Perché è importante**:
- Appunti = preparazione relatore (dettagli, script, timing)
- Slide = esperienza pubblico (visual, semplificato, d'impatto)
- Devono essere sincronizzati ma con livelli di dettaglio diversi

---

## 🎨 Regola: Font Monospace nelle Presentazioni

**Font monospace da usare nelle slide reveal.js** per codice, prompt, esempi tecnici:

**Migliori scelte** (in ordine di preferenza):
1. **Fira Code** - font con ligature, ottimo per codice
2. **JetBrains Mono** - leggibile, moderno
3. **Source Code Pro** - classico, affidabile
4. **Cascadia Code** - con ligature, Microsoft
5. **Fallback**: `Consolas, Monaco, 'Courier New', monospace`

**Dove applicare**:
- `presentation/*/index.html` sezione `<style>`
- Nelle classi `.code`, `.prompt`, o elementi `<code>`

**Esempio CSS**:
```css
code, pre, .prompt-box {
    font-family: 'Fira Code', 'JetBrains Mono', 'Source Code Pro', Consolas, Monaco, monospace;
    font-variant-ligatures: normal; /* abilita ligature */
}
```

---

## 📂 Struttura File Definitiva

```
ai-notes/
├── appunti/               # Dettagli per relatore
│   ├── esperimenti-60plus-DEFINITIVI.md
│   ├── script-esp1-come-chiedere-bene.md
│   ├── affermazioni-esp4-verita-o-bufala.md
│   ├── esempi-pratici-reali.md
│   ├── temi-da-sviluppare-draft.md
│   └── regole-sviluppo.md (questo file)
│
├── capitoli/              # Contenuti teorici capitoli
│   ├── capitolo-1-introduzione.md
│   ├── capitolo-2-cose-ia.md (da completare)
│   └── ...
│
├── presentation/          # Slide pubbliche reveal.js
│   ├── congresso-verbania/
│   ├── introduzione/
│   ├── cose-ia/
│   └── ...
│
├── guida-relatore.html    # Manuale web consultabile
├── index.html             # Homepage con link a tutto
└── README.md              # Info progetto
```

---

## 🔄 Workflow Git

Quando aggiungi/modifichi contenuti:

1. **Aggiungi/modifica file** (appunti + presentazione)
2. **Commit descrittivo**:
   ```bash
   git add appunti/*.md presentation/*/index.html
   git commit -m "Add: [cosa hai fatto]

   Dettagli:
   - [punto 1]
   - [punto 2]

   🤖 Generated with Claude Code

   Co-Authored-By: Claude <noreply@anthropic.com>"
   ```
3. **Push** immediatamente
4. **Verifica** su https://giobi.github.io/ai-notes/

---

## ✅ Checklist Pre-Commit

Prima di committare modifiche a esperimenti/capitoli:

- [ ] Appunti markdown aggiornati con dettagli completi?
- [ ] Slide reveal.js corrispondenti aggiornate?
- [ ] Font monospace corretto nelle slide (se applicable)?
- [ ] Timing coerente tra appunti e presentazione?
- [ ] Esempi sincronizzati?
- [ ] Note relatore aggiunte nelle slide (tasto S)?
- [ ] Test locale slide funzionanti (apri index.html)?

---

## 🎯 Principi Generali

**Per gli Appunti**:
- Dettaglio massimo
- Script word-by-word se serve
- Timing preciso
- Frasi pronte per gestione
- Piano B e varianti
- Checklist

**Per le Slide**:
- Visual d'impatto
- Testo minimo
- Font grandi e leggibili
- Immagini/emoji
- Animazioni quando utile
- Note relatore (S) con script

**Per Esempi e Prompt**:
- Font monospace figo
- Sfondo colorato per distinguere
- Copia-incolla facile
- Sintassi chiara

---

## 📌 Note Finali

Queste regole sono una guida, non legge assoluta. Se hai un motivo valido per deviarle, documentalo nel commit message.

**Obiettivo**: Mantenere appunti e presentazione sincronizzati senza duplicare inutilmente contenuto.

**Ricorda**: Appunti = per te (preparazione), Slide = per loro (esperienza).
