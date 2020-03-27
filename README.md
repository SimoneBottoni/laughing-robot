# Data Science for Business
Project for Data Science for Business 2020. Group 5: Simone Bottoni, Luca Bertaccini, Roberto Ripamonti.

#### Struttura Repository

- __Datasets:__ contiene i vari datasets utilizzati suddivisi in base alla provenienza. All'interno si trovano i csv nativi, i csv con i dati ripuliti e i notebook python contenenti il codice per la pulizia del dataset.
- __Statistics:__ contiene i vari notebook python suddivisi in base alla tipologia di dataset analizzato.
- __ScriptPostgres:__ contiene il notebook python con il codice per popolare il database PostgreSQL (eventualmente dovrà essere modificato l'url, l'utente, la password e il nome del database in caso di un utilizzo non in locale e non utilizzando il backup del database presente all'interno della cartella "DataBase BackUp").
- __DataBase BackUp:__ contiene il backup del database contenente i dati relativi ai datasets ripuliti utilizzati nella fase di analisi e dunque nei notebook della cartella "Statistics".
- __Graph Explain:__ contiene un notebook in cui andremo a commentare i grafici ricavati precedentemente.

#### Informazioni sull'analisi effettuata

L'analisi che andremo ad affrontare servirà a determinare eventuali analogie tra l'espansione del COVID-19 all'interno del territorio italiano e la sua espansione nel territorio francese.

Inoltre andremo ad analizzare i dati relativi ai 3 paesi maggiormente contagiati, per verificare eventuali analogie.

Useremo anche i dati relativi ai primi mesi del contagio, per analizzare l'espansione sul territorio di Wuhan, verificandone la distribuzione sul genere e sulle fasce di età.

Incroceremo i dati sopra citati con la ricchezza e l'eventuale spesa pubblica per la sanità, in modo da ricercare eventuali correlazioni con l'espansione dell'epidemia.

#### Riferimenti ai dataset utilizzati:

```bash
https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?end=2018&start=2018&view=bar

https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS

https://www.kaggle.com/imdevskp/corona-virus-report

https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1

https://github.com/pcm-dpc/COVID-19/

https://github.com/opencovid19-fr/data
```
