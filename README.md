# CCNL Commercio TDS Confcommercio per NotebookLM #

Questo repository contiene il **CCNL Commercio TDS (2019 + rinnovo 2024)** in formato markdown (.md) pronto per essere utilizzato da un NotebookLM di Google o altri programmi di IA, in particolare [RAG](https://it.wikipedia.org/wiki/Retrieval_augmented_generation).

Cos'è [NotebookLM](https://notebooklm.google/)? È un'applicazione gratuita di Google che consente di creare un assistente IA in cui si possono caricare documenti di vario tipo e che può essere usato per riassumere, consultare e studiare le fonti fornite.

Il formato dei documenti preferito dalle IA è il [markdown](https://it.wikipedia.org/wiki/Markdown), cioè un file in formato testo arricchito da informazioni di formttazione. Io ho trasformato i file PDF del CCNL in file markdown in modo da essere meglio compresi dal NotebookLM.

Indice dei file qui presenti:
- **Testo unico del CCNL Commercio TDS Confcommercio 2019**, inclusi: *allegati, allegati apprendistato, tabelle restibutive, protocolli aggiuntivi, appendice*.
- **Accordo di Rinnovo 2024**, inclusi: *protocollo nazionale sul lavoro agile, accordo integrativo del 22.3.2024*.

Di seguito le istruzioni per creare un "assistente sindacale" in NotebookLM al quale potrai porre domande sul CCNL.


## Come creare un NotebookLM sul CCNL Commercio

1. Scarica tutti i file dalla cartella `/md-ccnl-commercio-2019-2024` di questo repository: questo [link diretto](https://download-directory.github.io/?url=https://github.com/eventualo/ccnl-commercio-notebooklm/tree/master/md-ccnl-commercio-2019-2024) ti permette di scaricare uno ZIP con tutti i file: poi apri lo ZIP per avere i file pronti per l'uso.
1. Devi possedere un account Google: puoi crearlo a partire da https://accounts.google.com/signin.
1. Visita [https://notebooklm.google.com](https://notebooklm.google.com), accedi con il tuo account Google e clicca su **Crea Nuovo** per creare il primo NotebookLM.
1. Devi caricare le fonti: inserisci tutti i file che hai appena scaricato da questo repository (per fare prima puoi trascinarli tutti in un colpo solo).
1. Al termine del caricamento, il tuo "assistente sindacale" è pronto e puoi iniziare a consultarlo sul CCNL.

*Nota su NotebookLM: come tutti gli applicativi di IA potrebbe fornire risposte imprecise ed è bene sempre verificarle con le fonti. Il punto di forza di un'applicazione RAG come NotebookLM è che, se non trova una risposta, non tira a indovinare e si limita a dire che non ha trovato una risposta adeguata. Comunque, per ogni risposta che ottieni, puoi sempre verificarne la coerenza con le fonti citate nella risposta stessa.*

Caratteristiche e limiti della versione gratuita di NotebookLM:
- puoi fare domande tramite la chat: nota che c’è un limite di **50 domande al giorno**; (se vuoi puoi creare più NotebookLM con i file del CCNL così da avere di fatto più domande a disposizione);
- accetta al **massimo 50 fonti**;
- risponde sempre citando gli articoli del CCNL da cui trae le risposte, quindi puoi sempre controllare il testo originale del CCNL;
- puoi salvare le risposte in “note” così da avere alcune informazioni già pronte senza dover chiedere di nuovo;
- puoi usare le funzioni speciali come: “mappa mentale”, “riepilogo”, “podcast” (crea un audio con due voci che spiegano un argomento del CCNL a tua scelta. Limite: 3 podcast al giorno).

L'uso di NotebookLM è abbastanza intuitivo, ma se hai bisogno qui trovi la [guida ufficiale](https://support.google.com/notebooklm#topic=16164070).


## Come segnalare un'imprecisione nei file markdown del CCNL?

La conversione dei CCNL in file markdown è una procedura automatica, ma a seconda della complessità delle pagine può non essere precisa al 100%. Per cui ho sistemato le imprecisioni che ho trovato, ma si tratta di molte pagine e sicuramente ci sono ancora errori da correggere. 
Eventuali errori possono pregiudicare la comprensione da parte della IA e quindi la qualità delle sue risposte.

**Se a una tua domanda il NotebookLM, o altra applicazione IA che stai usando, ti ha dato una risposta imprecisa o sbagliata, per favore segnalamelo con questo form: https://forms.gle/7BfgGi3wQNXzXpdN9**

Se possibile cercherò di correggere il problema segnalato nel file markdown. Se hai dimestichezza con git e github e hai già individuato il problema in un file markdown, puoi anche aprirmi una pull request con le tue correzioni.
Grazie!