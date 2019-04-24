---

copyright:

  years: 1994, 2018

lastupdated: "2019-01-08"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:tip: .tip}
{:screen: .screen}
{:new_window: target="_blank"}


# Ottimizzazione dell'utilizzo della larghezza di banda
{: #cp_manbdwpool}

Il traffico della rete pubblica di dati che viene trasferito in uscita dai data center di IBM Cloud in tutto il mondo stabilisce gli addebiti della larghezza di banda in uscita. Gli addebiti dipendono dal luogo in cui risiede la risorsa che trasferisce i dati, dalla quantità di dati in uscita e dalle assegnazioni di larghezza di banda per cui sono idonei i tuoi prodotti cloud IBM acquistati.
{:shortdesc} 

I clienti possono ottimizzare l'utilizzo della larghezza di banda "raggruppando" insieme tutta la larghezza di banda per i server in un pool di larghezza di banda. Le eccedenze di larghezza di banda per i server in un pool di larghezza di banda vengono sommate nel loro insieme e tali eccedenze vengono calcolate solo se la larghezza di banda totale di tutti i server supera quella allocata totale per tutti i server rispetto alla misurazione a livello di singolo server. 

Le definizioni di pool sono elencate nella seguente tabella: 

| Pool      | Ubicazioni          |
| ------------- |:-------------:|
| USA    | DAL01<br/><br/>DAL02<br/><br/>DAL04<br/><br/>DAL07<br/><br/>DAL09<br/><br/>DAL10<br/><br/>DAL12<br/><br/>DAL13<br/><br/>HOU02<br/><br/>MON01<br/><br/>SEA01<br/><br/>SJC01<br/><br/>SJC03<br/><br/>SJC04<br/><br/>TOR01<br/><br/>WDC01<br/><br/>WDC04<br/><br/>WDC06<br/><br/>WDC07|
| Amsterdam e Londra | AMS01<br/><br/>AMS03<br/><br/>LON01<br/><br/>LON02<br/><br/>LON04<br/><br/>LON05<br/><br/>LON06<br/><br/>PAR01 |
| Australia | MEL01<br/><br/>SYD01<br/><br/>SYD04<br/><br/>SYD05 |
| Brasile | SAO01 |
| Francoforte | FRA02<br/><br/>FRA04<br/><br/>FRA05 |
| India | CHE01 |
| Italia | MIL01 |
| Corea del Sud | SEO01 | 
| Messico | MEX01 | 
| Norvegia | OSL01 | 
| Singapore, Hong Kong & Tokyo | HKG02<br/><br/>SNG01<br/><br/>TOK02<br/><br/>TOK04<br/><br/>TOK05 |
{:caption="Tabella 1. Definizioni di pool" caption-side="top"}


## Modifica di un pool di larghezza di banda
{: #cp_modbdwpool}

Una volta creato un pool di larghezza di banda, se sei un utente autorizzato, puoi accedere al pool in qualsiasi momento. Accedi al pool di larghezza di banda per visualizzare i dispositivi associati al pool, aggiungere dispositivi o rimuovere i dispositivi dal pool. Utilizza la seguente procedura per accedere a un pool:

1. Accedi al portale clienti con le tue credenziali univoche.
2. Dal menu, seleziona **Rete** > **Larghezza di banda** > **Pool** per accedere alla finestra Pool di larghezza di banda.
3. Fai clic su **Nome pool** per accedere al pool. Viene visualizzato ogni dispositivo associato al pool.
4. Dalla scheda **Modifica**, puoi rinominare il pool, aggiungere un dispositivo o rimuovere un dispositivo dal pool.
  * Per rinominare il pool, immetti il nuovo nome del pool nel campo che ha il nome pool corrente.
  * Per aggiungere un dispositivo al pool, dall'elenco **Aggiungi server**, seleziona il nome del dispositivo e fai clic su **Seleziona**.
  * Per rimuovere un dispositivo da un pool, dall'elenco **Rimuovi server**, seleziona il dispositivo e fai clic su **Seleziona**.
5. Fai clic su **Modifica rack**.
6. Fai clic sul link **Visualizza tutti i pool di larghezza di banda** per tornare alla finestra Pool di larghezza di banda.
