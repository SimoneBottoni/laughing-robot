# Data Science for Business
Project for Data Science for Business 2020. Group 5: Simone Bottoni, Luca Bertaccini, Roberto Ripamonti.

#### Struttura Repository

- __Transformations Notebook:__ questo notebook contiene la transformation pipeline dei vari dataset utilizzati.
- __Analysis Notebook:__ in questo notebook viene presentata l'analisi effettuata con i relativi grafici.
- __Datasets:__ contiene i vari datasets utilizzati suddivisi in base alla provenienza. All'interno si trovano i csv nativi, i csv con i dati ripuliti e i notebook python contenenti il codice per la pulizia del dataset.
- __Statistics:__ contiene i vari notebook python suddivisi in base alla tipologia di dataset analizzato.
- __ScriptPostgres:__ contiene il notebook python con il codice per popolare il database PostgreSQL (eventualmente dovrà essere modificato l'url, l'utente, la password e il nome del database in caso di un utilizzo non in locale e non utilizzando il backup del database presente all'interno della cartella "DataBase BackUp").
- __DataBase BackUp:__ contiene il backup del database contenente i dati relativi ai datasets ripuliti utilizzati nella fase di analisi e dunque nei notebook della cartella "Statistics".
- __Json:__ in questa cartella si trova il json utilizzato a supporto del download dei dataset.

#### Riferimenti ai dataset utilizzati:

```bash
Posti Letto Ospedali: http://www.dati.salute.gov.it/dati/dettaglioDataset.jsp?menu=dati&idPag=96  
Protezione Civile: https://github.com/pcm-dpc/COVID-19  
Francia: https://github.com/opencovid19-fr/data  
Open/Line_List: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset  
Mondo: https://www.kaggle.com/imdevskp/corona-virus-report  
Istat: http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1  
GDP: https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?end=2018&start=2018&view=bar  
Health: https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS  
Containment Measures: https://www.kaggle.com/paultimothymooney/covid19-containment-and-mitigation-measures
Temperature: https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data
```
