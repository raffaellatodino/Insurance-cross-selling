# Cross-selling-assicurativo
Master in Data Science: progetto modulo di fondamenti di Machine Learning.  

AssurePredict è una compagnia di assicurazioni leader nel settore, specializzata nell'offrire soluzioni innovative per la gestione del rischio. Questo progetto mira a creare un modello predittivo in grado di individuare potenziali opportunità di cross-selling per clienti esistenti, identificando quelli che potrebbero essere interessati ad acquistare una polizza aggiuntiva per il loro veicolo.  

## Obiettivo del Progetto
L'obiettivo è sviluppare un modello di machine learning che preveda se i clienti, che attualmente hanno un'assicurazione sanitaria, potrebbero essere interessati a sottoscrivere una polizza assicurativa per il loro veicolo.  
Il modello aiuterà AssurePredict a migliorare l'efficacia delle proprie strategie di cross-selling e ad aumentare la penetrazione nel mercato.

## Dataset
Il dataset contiene informazioni dettagliate sui clienti e sul loro comportamento assicurativo. Le caratteristiche principali del dataset sono:  

- id: identificativo univoco del cliente.  
- Gender: sesso del cliente.  
- Age: età del cliente.  
- Driving_License: 1 se il cliente possiede la patente di guida, 0 altrimenti.  
- Region_Code: codice univoco della regione di residenza del cliente.  
- Previously_Insured: 1 se il cliente ha già un veicolo assicurato, 0 altrimenti.  
- Vehicle_Age: età del veicolo del cliente.  
- Vehicle_Damage: 1 se il cliente ha avuto incidenti o danni al veicolo in passato, 0 altrimenti.  
- Annual_Premium: importo annuale del premio assicurativo pagato dal cliente.  
- PolicySalesChannel: canale utilizzato per la vendita della polizza (es. email, telefono, di persona).  
- Vintage: giorni da cui il cliente è assicurato con AssurePredict.  
- Response: 1 se il cliente ha accettato la proposta di cross-sell, 0 altrimenti.
