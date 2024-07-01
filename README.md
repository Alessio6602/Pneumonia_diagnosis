

## Pneumonia_diagnosis
Questa repository contiene il progetto di tesi svolto da Alessio Gatto, presso l'Università degli Studi di Bari "Aldo Moro". Il progetto consiste nella creazione e valutazione di un modello di Machine Learning basato sull'architettura MobileNet. L'obiettivo del progetto è permettere al modello addestrato di diagnosticare correttamente la polmonite ai pazienti, e di evidenziare le zone ritenute infette.

## Dataset
Il dataset utilizzato è presente sul sito Kaggle col nome di ChestXRay2017, scaricabile dal seguente link: https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images/data
Alternativamente è possibile utilizzare la versione ridotta del dataset utilizzata durante gli esperimenti direttamente dalla repository.
## Setup
Salvare il dataset sul drive con il nome ChestXRay2017, e creare al suo interno. se non presente, una cartella "val" con all'interno due cartelle: "PNEUMONIA" e "NORMAL".

## Utilizzo
Aprire google Colab con il proprio account, dopodichè selezionare carica e aprire il file Pneumonia_diagnosis.ipynb. Durante l'esecuzione sarà necessario fornire l'autorizzazione ad accedere al proprio drive. Il programma permette di addestrare il modello e salvarlo sul drive. Per eseguire le predizioni su un modello già addestrato eseguire solo le celle poste dopo la scritta "Esecuzione su modello pre-addestrato".

Le librerie necessarie verranno installate durante l'esecuzione: -tensorflow 2.15; -tf_keras_vis 0.87;

## Contributi 

[@Alessio Gatto](https://github.com/Alessio6602/Pneumonia_diagnosis.git)


