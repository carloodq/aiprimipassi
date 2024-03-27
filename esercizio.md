# Esercizio 1
carica il nuovo dataset in un DataFrame chiamato **home_data** (train.csv)

Mostra le statistiche

Qual è la grandezza media del lotto (arrotondata all'intero più vicino)

Ad oggi, qual è la casa più nuova (anno corrente - anno di costruzione)

La casa più recente nei tuoi dati non è così nuova. Alcune potenziali spiegazioni:

1. Non hanno costruito case recentemente dove sono stati raccolti questi dati.
2. I dati sono stati raccolti molto tempo fa.

# Esercizio 2
- Specifica la tua variabile target - creane una Series e chiamala y

- Usiamo questa lista di variabili per addestrare il modello

LotArea
YearBuilt
1stFlrSF
2ndFlrSF
FullBath
BedroomAbvGr
TotRmsAbvGrd

- Controlla X mostrando le prime 5 righe
- Crea un DecisionTreeRegressor . Fitta il modello utilizzando i dati in X e y di prima.
- usa predict per predirre il prezzo su tutto X. Cosa noti se confronti i valori predetti con quelli reali

# Esercizio 3

Riprendendo da dove eravamo rimasti prima
- Usa la funzione train_test_split per suddividere il dataset
- Crea un DecisionTreeRegressor e fittalo al dataset giusto. Imposta il random state su 1.
- Fai le predizioni sul validation set
- Calcola il MAE sul validation set

# Esercizio 4

Scrivi una funzione get_mae che prende train e val (X e y) e anche max_leaf_nodes e restituisce il MAE
Per le seguenti opzioni di max leaf nodes crea un loop per trovare il miglior MAE
candidate_max_leaf_nodes = [5, 25, 50, 100, 250, 500]
Qual è la profondità associata con il minor MAE?





