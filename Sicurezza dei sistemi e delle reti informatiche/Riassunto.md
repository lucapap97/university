# Riassunto
## Parte 1
### Confidentiality, Avaiability e Integrity
1. **integrita'**
	- **dati**
	assicurare che dati e programmi sono stati modificati solo in una specifica e autorizzata maniera.
	- **sistema**
	assicurare che il sistema esegua le sue funzioni in maniera inalterata da manipolazioni volontarie/involontarie
2. **disponibilita'**
	- **dati**
	accesso tempestivo e affidabile
	- **sistema**
	il servizio esegue correttamente e non nega l'accesso a chi è autorizzato
3. **confidenzialita'**
	- **dati**
	le informazioni riservate non sono disponibili da utenti non autorizzati
	- **privatezza**
	gli individui possono controllare quale informazione può essere raccolta e come può 	essere comunicata (e anche a chi)

### Minaccia
    possibile violazione della sicurezza
### Attacco
    Tentativo di fuggire alla sicurezza
- Passivo: ascoltare il traffico, analizzarlo
- Attivo: modificare il flusso, creare flusso inesistente

### Meccanismo
    Insieme di tecniche, strumenti utilizzati per attuare una politica
### Politica
    Scelte prese in risposta di un determinato evento

### X800
Meccansismi:
-   **Specifici**: incorporati nell'approprioato livello per fornire alcuni dei servizi di sicurezza OSI

- **Pervasivi**: non sono specifici e eno nappartengono ad un particolare servizio di sicurezza o livello OSI

### Tipi di minaccia:
-   **Divulgazione**: accesso non autorizzato ai dati
-   **Inganno**: accettazione di dati falsi
-   **Interruzione**: interruzione del corretto funzionamento
-   **Usurpazione**: controllo non autorizzato del sistema

### Principi fondamentali:
-   **Fail safe defaults**: se non è esplicitato un soggetto non deve avere accesso ad un oggetto. Se un osggetto non è in grado di completare una a zione, dovrebbe annullare tutto e riportare lo stato iniziale sicuro.

-   **Economy**: deve essere tutto il più semplice possibile.

-    **Complete mediation**: tutti gli accessi devono essere controllati per assicurarsi che siano autorizzati.

-   **Open design**: la sicurezza di un meccanismo non deve dipendere dalla segretezza della sua progettazione.

-   **Separation of privilege**: il sistema non dovrebbe concedere l'autorizzazione in base ad una singola condizioe.

-   **Least privileges**: ad un soggetto vengono concessi solo i privilegi di cui ha bisogno.

-   **Psychological Acceptability**: le politiche di sicurezza non devono rendere l'accesso alla risorsa più complicato.




