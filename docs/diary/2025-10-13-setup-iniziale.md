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

## Note Finali

Setup completato con successo. La struttura di documentazione è ora pronta per tracciare lo sviluppo del progetto. Il Capitolo 1 ha buone basi e idee concrete per l'espansione. Il prossimo step sarà decidere quali idee integrare e iniziare a lavorare sugli altri capitoli.

**Stato**: ✅ Setup completato
**Prossima sessione**: Sviluppo contenuti capitoli o lavoro su progetto circus

---

*Fine sessione: 2025-10-13 ~07:20 UTC*
