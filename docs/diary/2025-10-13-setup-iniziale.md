# 2025-10-13 - Setup Iniziale Progetto AI Notes

**Data**: 2025-10-13
**Ora inizio**: 07:15 UTC
**Obiettivo**: Clonare il progetto AI Notes, creare struttura documentazione e iniziare brainstorming Capitolo 1

## Attività

### Task 1: Clone Repository
- Clonato repository da https://github.com/giobi/ai-notes
- Posizione: `/home/claude/app/ai-notes/`
- Repository git attivo e funzionante

### Task 2: Creazione Struttura Documentazione
Creata nuova cartella `/docs` con:

#### File creati:
- `docs/README.md` - Panoramica della documentazione
- `docs/base-prompt.md` - Comportamento agenti AI
- `docs/project-info.md` - Informazioni generali progetto
- `docs/diary/README.md` - Guida all'uso del diary

#### Contenuti documentati:
- Struttura del progetto (appunti, capitoli, slides, presentation, risorse)
- Obiettivo del corso (90 minuti, Università Terza Età)
- 4 capitoli principali del corso
- Convenzioni di sviluppo
- Tecnologie usate (reveal.js, Jekyll, GitHub Pages)

### Task 3: Analisi Contenuti Esistenti
Esaminati file esistenti:
- `capitoli/capitolo-1-introduzione.md` - Ben strutturato (Asimov, AGI, ChatGPT)
- `capitoli/capitolo-2-cos-e-ia.md` - Bozza da sviluppare
- `appunti/idee-generali.md` - Outline generale dei 4 capitoli
- Presentazioni reveal.js già create per capitoli 1-2 e congresso-verbania

### Task 4: Brainstorming Capitolo 1
Creato `appunti/capitolo-1-idee-espansione.md` con:

#### Idee chiave aggiunte:
1. **Esempi visivi**: Film (2001, Her, Io Robot), timeline grafica
2. **Aneddoti storici**: Deep Blue (1997), AlphaGo (2016), Test di Turing
3. **Concetti chiave**: Big Data, potenza calcolo, differenza IA vs automazione
4. **Elementi interattivi**: Demo ChatGPT live, quiz coinvolgenti
5. **Gestione tempo**: Struttura 15 minuti con domande

#### Suggerimenti pedagogici:
- Riferimenti culturali per terza età
- Evitare tecnicismi
- Collegare a esperienze quotidiane
- Incoraggiare domande durante

#### Risorse da preparare:
- Video clip (max 30 sec)
- Immagini e timeline
- Demo ChatGPT
- Piano B se tecnologia fallisce

## Struttura Progetto Verificata

```
app/ai-notes/
├── appunti/
│   ├── idee-generali.md
│   ├── link-utili.md
│   ├── cambiamenti.md
│   └── capitolo-1-idee-espansione.md ← NUOVO
├── capitoli/
│   ├── capitolo-1-introduzione.md
│   └── capitolo-2-cos-e-ia.md
├── slides/
├── presentation/
│   ├── congresso-verbania/
│   ├── cose-ia/
│   └── introduzione/
├── risorse/
├── docs/ ← NUOVO
│   ├── README.md
│   ├── base-prompt.md
│   ├── project-info.md
│   └── diary/
│       ├── README.md
│       └── 2025-10-13-setup-iniziale.md
├── _config.yml
├── index.html
├── README.md
└── HOWTO.md
```

## Decisioni Tecniche

1. **Struttura documentazione**: Creata cartella `/docs` separata dal contenuto del corso per mantenere organizzazione chiara
2. **Diary format**: Un file per sessione con formato YYYY-MM-DD-descrizione.md
3. **Base prompt**: Configurato per lingua italiana, pubblico non tecnico, tono amichevole ma professionale

## Prossimi Task Identificati

### Progetto AI Notes
- [ ] Sviluppare ulteriormente Capitolo 2, 3, 4
- [ ] Raccogliere risorse video/immagini per Capitolo 1
- [ ] Creare demo ChatGPT preparate
- [ ] Timeline grafica evoluzione IA

### Progetto Circus (separato)
- [ ] Mettere circus a cron
- [ ] Migrare "jane" su circus (da capire cos'è jane)

## Note sul Contesto

**Deadline**: Tra 2 mesi il corso dovrà essere pronto per la presentazione
**Pubblico**: Università della Terza Età - non tecnico
**Durata**: 90 minuti totali (circa 20 min per capitolo + domande)

## Riferimenti

- Repository: https://github.com/giobi/ai-notes
- GitHub Pages: https://giobi.github.io/ai-notes
- Tecnologie: reveal.js, Jekyll, Markdown

### Task 5: Sviluppo Intro Tecnica
Creato `appunti/intro-tecnica-autocompletamento.md` e `appunti/intro-alternative.md`

#### Intro Tecnica - Concept "Dall'Autocompletamento a ChatGPT"
**File**: `appunti/intro-tecnica-autocompletamento.md`

Script completo (4 minuti) che spiega:
1. **Esperienza quotidiana**: Autocompletamento su WhatsApp
2. **Meccanismo base**: Statistiche, pattern recognition, milioni di messaggi
3. **Salto quantitativo**: Da 1M frasi a 300B parole (ChatGPT)
4. **Demo pratica**: "Il gatto è salito sul..." - coinvolgimento pubblico
5. **Domanda filosofica**: "È davvero intelligente o solo statistica sofisticata?"

**Punti di forza**:
- Demistifica l'IA partendo da esperienza condivisa
- Nessun tecnicismo (no "neural networks", solo "pattern")
- Accessibile per terza età
- Introduce dubbio per Cap. 4 (etica e futuro)

#### 3 Alternative per Intro Emozionale
**File**: `appunti/intro-alternative.md`

1. **Aneddoto Nonna** - Storia vera truffa voce clonata (emotivo, forte impatto)
2. **Quiz Interattivo** - Indovina immagini reali vs AI (sorprendente, coinvolgente)
3. **Confronto Generazionale** - Luna 1969 → HAL 9000 → oggi (nostalgico, celebrativo)

### Task 6: Creazione Presentazione Reveal.js
Creata presentazione web interattiva completa

**File**: `presentation/intro-autocompletamento/index.html`

Presentazione reveal.js con:
- 15 slide complete con animazioni e transizioni
- Design responsive e professionale
- Esempi interattivi preparati
- Box highlights per concetti chiave
- Confronto visivo scale (1M vs 300B)
- Diagramma flusso semplificato
- Transizione naturale verso Cap. 1

**Elementi visivi**:
- Emoji per rendere più friendly
- Box colorati per evidenziare concetti
- Grid comparison telefono vs ChatGPT
- Question box per domande filosofiche

### Task 7: Git Commit
**Commit**: `4e417f0`
**Messaggio**: "Aggiunta presentazione introduttiva e materiali di brainstorming"

File committati:
- 9 files changed, 1202 insertions(+)
- Tutti i nuovi appunti, docs e presentazione

**Nota**: Push richiede autenticazione (repository usa HTTPS). Da fare manualmente.

## Note Finali

### Sessione Completa
Setup e primo sviluppo contenuti completati con successo:

✅ **Infrastruttura**: Docs, diary, base-prompt creati
✅ **Brainstorming**: 3 alternative intro + espansione Cap. 1
✅ **Contenuto tecnico**: Script completo intro autocompletamento
✅ **Presentazione**: Slide reveal.js pronte per l'uso
✅ **Git**: Commit fatto, push da fare manualmente

### Deliverables Pronti
1. **Presentazione web**: `presentation/intro-autocompletamento/` accessibile via browser
2. **Script dettagliato**: `appunti/intro-tecnica-autocompletamento.md` con timing e note
3. **Opzioni alternative**: `appunti/intro-alternative.md` per variare approccio
4. **Idee espansione**: `appunti/capitolo-1-idee-espansione.md` per arricchire contenuto

### Prossimi Step Suggeriti
- [ ] Test presentazione in browser locale
- [ ] Push manuale su GitHub
- [ ] Decidere quale intro usare (tecnica vs emozionale vs ibrida)
- [ ] Sviluppare Capitoli 2, 3, 4
- [ ] Raccogliere risorse multimediali (video, immagini)

**Stato**: ✅ Prima sessione completata con successo
**Tempo totale**: ~30 minuti
**Output**: 9 nuovi file, 1200+ righe di contenuto

---

*Fine sessione: 2025-10-13 ~07:35 UTC*
